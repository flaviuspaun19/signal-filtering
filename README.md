# Signal Filtering in LabVIEW

This repository contains a LabVIEW Virtual Instrument (VI) demonstrating fundamental concepts of **signal filtering**, specifically focusing on the application of a **Low-Pass Filter (LPF)** to remove high-frequency noise.

## Project Overview

The project utilizes LabVIEW's graphical programming environment to implement a real-time signal processing algorithm. The VI allows a user to:
1.  Generate a test signal (implied by the block diagram structure).
2.  Apply a filter (specifically a **Low-Pass Filter** is discussed in the conclusion).
3.  Visualize the unfiltered and filtered signals on a **Waveform Graph**.

### Filter Types Demonstrated

While the conclusion highlights a Low-Pass Filter, the concept of signal filtering covers four main types:
* **Low-pass filters**: Pass frequencies below a cutoff frequency.
* **High-pass filters**: Pass frequencies above a cutoff frequency.
* **Band-pass filters**: Pass a specific range of frequencies.
* **Band-stop filters**: Block a specific range of frequencies.

The VI's implementation uses built-in LabVIEW filter functions, which can include types like **Butterworth**, **Chebyshev**, or **FIR** filters.

## Key Features

* **Real-Time Control**: The **Cutoff Frequency** can be adjusted on the Front Panel, allowing users to experiment with various filtering effects in real-time.
* **Graphical Interface**: The project showcases the advantage of LabVIEW for designing complex signal processing without extensive traditional coding.
* **Signal Improvement**: It effectively demonstrates **noise reduction** by removing unwanted high-frequency noise from the signal.

## Prerequisites

To run this VI, you will need:
* **NI LabVIEW Development System** (The version used for this project or a compatible newer version).

## Usage

1.  Clone this repository to your local machine.
2.  Open the `VI project.vi` file in LabVIEW.
3.  Run the VI (The **Run** button on the LabVIEW toolbar).
4.  Use the **Sampling Frequency** and **Low Cutoff Freq** controls on the **Front Panel** to adjust the filtering parameters.
5.  Observe the original and filtered signals on the **Waveform Graph**.
6.  Click the **STOP** button to end the execution.

### Front Panel Screenshot


### Block Diagram Screenshot


## Conclusion from Project

[cite_start]The project successfully demonstrates the effectiveness of filtering in signal processing, proving that applying a filter (like the LPF) can effectively remove unwanted noise and condition a signal for further analysis or data transmission[cite: 17, 18, 58].
