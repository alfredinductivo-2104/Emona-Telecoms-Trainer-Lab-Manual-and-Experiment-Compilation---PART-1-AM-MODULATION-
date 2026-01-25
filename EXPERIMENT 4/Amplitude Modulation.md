# AMPLITUDE MODULATION

---

## INTRODUCTION:

Amplitude Modulation (AM) is a technique used in electronic communication. It is most commonly used for transmitting information via radio waves. In AM, the amplitude of a high-frequency carrier signal is varied in proportion to the instantaneous amplitude of the message or information signal, while the frequency remains constant. This method allows audio, voice, or other signals to be transmitted over long distances and received by AM radio receivers.

---

## OBJECTIVE

In this experiment, the students will generate a real AM signal and observe how the amplitude of a carrier changes according to the message signal. Additionally, the experiment will explore how different inputs, like a sine wave or speech, affect the AM output and teach students to use the Emona Telecoms-Trainer 101 to visualize and analyze AM signals on an oscilloscope.

---

## EQUIPMENT TO BE USED:
1. Emona Telecoms-Trainer 101 (plus power-pack)
2. Dual channel 20Mhz Oscilloscope
3. Two Emona Telecoms-Trainer Oscilloscope lead
4. Assorted Emona Telecoms-Trainer 101 patch leads
5. One set of Headphones (stereo)

---

## THINGS YOU MAY NEED TO KNOW
- **Amplitude** refers to the magnitude of a signal and is measured in volts (V). It is commonly measured either from the center of the waveform to its maximum value (peak voltage) or from the minimum to the maximum value (peak-to-peak voltage).
- The **Period** of a signal is the time required to complete one full cycle and is measured in seconds (s). For faster signals, the period may be expressed in milliseconds (ms) or microseconds (µs).
- **Frequency** is the number of cycles that occur in one second and is measured in hertz (Hz). Higher frequencies are commonly expressed in kilohertz (kHz) or megahertz (MHz).
- Two signals that are in phase with each other are synchronized. That is, they go up and down at the same time.
- Two signals that out of phase are not synchronized. That is, they are out of step with each other.
- **Phase difference** describes how much two signals are out of phase and is measured in degrees (°).
- A sinewave is a repetitive signal with the shape.
- A cosine wave is simply a sinewave that is out of phase with another sinewave by exactly 90°.

---

## SUMMARY OF FINDINGS AND RESULTS

### 1. Generating a AM signal

In the fourth experiment, the focus shifts to generating a real AM signal by implementing its mathematical model. This allows us to examine the AM signal and compare it with the original message signal. In the first setup, a 2 kHz sine wave is used as the message signal and applied to the VCO. The resulting signal is then passed through the Multiplier Module together with a 100 kHz sine wave, which serves as the carrier. Through this process, an amplitude-modulated (AM) signal is generated using a simple message signal.


<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/83f9888a-d25d-4ab3-b29a-ffde294ec113" />

It is represented by this Block Diagram:

<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/75ca7dd9-f244-44b1-940e-84a79d59d1b2" />

1.1 The oscilloscope display provides a direct comparison between the source and the modulated result: the red signal (Channel 1) represents the original message signal, while the yellow trace (Channel 2) displays the resulting AM output signal. It is observed that a lot of changes happen from the original signal. First, it is very observable that the characteristics such as the output voltage, frequency, and the bandwidth has increase. Additionally, the vertical peaks of the yellow signal precisely track the voltage fluctuations of the red signal, confirming that the message has been successfully impressed onto the carrier's amplitude without distortion or over-modulation.

<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/f4553fd5-db3d-45d0-9967-0ada62f2a511" />

### 2. Generating an AM Signal using Speech

After that, the Speech Module is used, and the originating signal is changed from a sine wave to an actual voice or speech signal. This allows us to observe a real AM signal produced by modulating a carrier with a live audio input.

<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/6282d194-ee19-4cc7-b71e-4aa65cb09a26" />

2.1 When the 2khz sine wave is replaced with a microphone input, the oscilloscope display becomes significantly more dynamic and irregular. It is observe that the output signal is no longer shows a steady, repeating pattern but instead displays the complex, jagged voltage fluctuations characteristic of real-time audio or speech. Additionally, as we speak to the microphone with different volume of voice the carrier wave whose envelope constantly shifts in shape and thickness changes depending on the volume and pitch of the voice.

<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/90eb0ffb-7670-422c-8096-ac7a61a16de0" />

https://github.com/user-attachments/assets/6ebac3bb-335a-45e9-971e-896513dc6c4f

---

## Lab Questions

**Q1: In what way is the Adder module's output different from the original 2 kHz sine?**  
The output of the Adder Module differs from the original 2 kHz sine wave in **amplitude and phase**. When two sine waves are added together, the resulting waveform depends on the relative amplitudes and phase differences of the input signals. If one input is phase-shifted, the output remains a 2 kHz sine wave but exhibits a different phase and possibly a different peak amplitude compared to the original input signal.

**Q2: What feature of the Multiplier output suggests it is an AM signal?**  
The Multiplier output shows a high-frequency carrier whose **amplitude varies in accordance with the low-frequency message signal**. This changing envelope is the key feature that identifies the signal as an amplitude-modulated (AM) signal. The outline (envelope) of the waveform follows the shape of the message signal.

**Q3: Is one of the signals in the AM complex a 2 kHz sine wave?**  
Yes. One of the signals in the AM complex is the 2 kHz sine wave, which serves as the **message (modulating) signal**. This signal controls the amplitude of the high-frequency carrier during the modulation process.

**Q4: Why is there a signal out of the Multiplier even when not speaking (Speech module)?**  
There is still a signal at the output of the Multiplier because the **carrier signal is always present**, even when there is no speech input. When no speech is applied, the modulating signal is essentially zero or constant, resulting in an unmodulated carrier at the Multiplier output.

---

## Conclusion
After analyzing the gathered data and observations about the Amplitude Modulation process and output, the following conclusions have been made:
- The AM experiments demonstrated how a carrier signal can be effectively modulated with a message signal, whether a simple sine wave or a real speech input. Observing the AM signals reinforced the understanding of how information is transferred through variations in the carrier’s amplitude.
- The oscilloscope displays confirmed that the envelope of the AM signal accurately follows the message signal, showing that the modulation process preserves the information without distortion when properly implemented.
- Using the Multiplier Module effectively combined the message and carrier signals, producing a high-frequency output with an amplitude that varies according to the input, which is the essential characteristic of AM.
- The Real-time speech modulation demonstrated that AM can handle complex, dynamic inputs, with the carrier envelope changing according to voice intensity and pitch, providing insight into practical audio transmission.
- The experiments also highlighted the role of phase and amplitude in shaping the resulting waveform when multiple signals are combined, as seen with the Adder Module.






