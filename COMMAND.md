# WebSocket Commands in MainWindow::onMessageReceived

| Command                          | Action Description                                                                                    |
|----------------------------------|-------------------------------------------------------------------------------------------------------|
| ConfirmIndiDriver                | Confirms the INDI driver with the specified driver name.                                             |
| ConfirmIndiDevice                | Confirms the INDI device with the specified device and driver names.                                 |
| SelectIndiDriver                 | Selects the INDI driver from the specified group and list number.                                    |
| takeExposure                     | Initiates an exposure for the specified duration.                                                    |
| focusSpeed                       | Sets the focus speed and sends a success message.                                                    |
| focusMove                        | Moves the focuser left, right, or to a target position based on the command.                        |
| RedBox                           | Updates the red box dimensions for capturing.                                                        |
| RedBoxSizeChange                 | Changes the size of the red box and sends the main camera size.                                     |
| AutoFocus                        | Initiates the auto-focus process.                                                                     |
| StopAutoFocus                    | Stops the auto-focus process.                                                                         |
| abortExposure                    | Aborts the current exposure.                                                                          |
| connectAllDevice                 | Connects all devices.                                                                                 |
| disconnectAllDevice              | Disconnects all devices and clears the system device list.                                           |
| MountMoveWest                    | Moves the mount west.                                                                                 |
| MountMoveEast                    | Moves the mount east.                                                                                 |
| MountMoveNorth                   | Moves the mount north.                                                                                |
| MountMoveSouth                   | Moves the mount south.                                                                                |
| MountMoveAbort                   | Aborts the mount's current motion.                                                                    |
| MountPark                        | Parks the mount and sends the park status.                                                           |
| MountTrack                       | Starts or stops tracking with the mount and sends the track status.                                  |
| MountHome                        | Force to set the current position as Home position                                                   |
| MountSYNC                        | Synchronizes the mount's position.                                                                    |
| MountSpeedSet                    | Sets the mount's speed and sends a success message.                                                  |
| ImageGainR                       | Sets the gain for the red channel.                                                                    |
| ImageGainB                       | Sets the gain for the blue channel.                                                                   |
| ScheduleTabelData                | Processes the schedule table data.                                                                    |
| MountGoto                        | Moves the mount to the specified RA and Dec coordinates.                                             |
| StopSchedule                     | Stops the current schedule.                                                                            |
| CaptureImageSave                 | Saves the captured image.                                                                              |
| getConnectedDevices              | Retrieves and sends the list of connected devices.                                                   |
| getStagingImage                  | Sends the status of the staging image.                                                                |
| StagingScheduleData              | Sends the staging schedule data.                                                                       |
| getStagingScheduleData           | Retrieves and sends the staging schedule data.                                                        |
| getStagingGuiderData             | Sends the guider data for the last 50 entries.                                                       |
| ExpTimeList                      | Saves the exposure time list.                                                                         |
| getExpTimeList                   | Retrieves and sends the exposure time list if available.                                             |
| getCaptureStatus                 | Sends the current capture status of the main camera.                                                 |
| SetCFWPosition                   | Sets the CFW position and sends a success message.                                                   |
| CFWList                          | Retrieves and saves the CFW slot names.                                                               |
| getCFWList                       | Retrieves and sends the CFW list.                                                                     |
| ClearCalibrationData             | Clears the calibration data.                                                                           |
| GuiderSwitch                     | Toggles the guiding status and sends the status message.                                             |
| GuiderExpTimeSwitch              | Sets the exposure time for the guider.                                                                |
| getGuiderSwitchStatus            | Sends the current status of the guider switch.                                                        |
| SolveSYNC                        | Solves the sync for the telescope.                                                                    |
| ClearDataPoints                  | Clears the FWHM data points.                                                                          |
| ShowAllImageFolder               | Shows all image files in the specified folder.                                                       |
| MoveFileToUSB                    | Moves specified files to the USB drive.                                                               |
| DeleteFile                       | Deletes specified files.                                                                                |
| USBCheck                         | Checks the USB drive status and remaining space.                                                        |
| SolveImage                       | Initiates the solving of an image.                                                                    |
| startLoopSolveImage              | Starts the loop solving of an image.                                                                   |
| stopLoopSolveImage               | Stops the loop solving of an image.                                                                    |
| StartLoopCapture                 | Starts capturing images in a loop.                                                                     |
| StopLoopCapture                  | Stops the loop capturing process.                                                                      |
| getStagingSolveResult            | Retrieves and sends the staging solve results.                                                        |
| ClearSloveResultList             | Clears the list of solve results.                                                                      |
| getOriginalImage                 | Retrieves and saves the original image.                                                                |
| saveCurrentLocation              | Saves the current location coordinates.                                                                |
| getCurrentLocation               | Sends the current location coordinates if available.                                                  |
