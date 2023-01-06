# frc-analysis
Python libraries for FRC log analysis

For an example of usage, see
[this example](https://colab.research.google.com/drive/1GXLz_uzQjFapCOq4pNkRYJOsbTSV5BKV).

It uses Google's "Colab" tool, which is Jupyter notebooks in the cloud.

The general workflow is:

* Stick a USB drive in the RoboRIO.
* Use DataLogManager to log from the RoboRIO to USB.
* Upload the log to the "frc-logs" repo.
* Make a copy of the Colab notebook.
* Load the new log into it and make some charts!
