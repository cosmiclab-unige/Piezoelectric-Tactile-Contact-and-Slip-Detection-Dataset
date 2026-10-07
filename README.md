Dataset: Flexible Piezoelectric Tactile Sensing – Raw PVDF Signals

This repository contains the raw tactile dataset associated with the paper:

“Contact Events and Slip Onset Detection Based on a Piezoelectric Sensing System and Embedded Machine Learning.”

The dataset contains raw voltage signals acquired from a flexible 8-sensor P(VDF-TrFE) piezoelectric tactile array integrated into a soft silicone fingertip and mounted on the z-axis of a Cartesian robot. The tactile signals were recorded at a sampling rate of 2 kHz during a sequence of three tactile interaction events: contact onset, slip onset, and contact release.
Dataset Description

The main dataset was collected over 300 repeated experimental trials. For each trial, segments corresponding to contact onset, slip onset, and contact release were extracted from the raw tactile signals and labeled using synchronized force/torque measurements as the ground-truth reference, resulting in 900 event samples (300 per event).
An additional dataset was collected to evaluate the approach across different surface textures: woven fabric, leather, and white paper. For each texture, 50 trials were acquired following the same experimental protocol.

Parameters: 8 P(VDF-TrFE) sensing channels; sampling rate: 2 kHz; data type: raw voltage signals; events: Contact Onset → Slip Onset → Contact Release; main dataset: 300 trials; additional texture dataset: 150 trials; evaluated window sizes: W = {16,32,48,64,80\} samples.

