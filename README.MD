# ESP-IDF Project Setup Guide

## Creating the First Blink Project

### To create this project in **VS Code**:

1. Select **View** → **Command Palette** in the top menu.

   **OR**

2. Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>.

After pressing <kbd>Enter</kbd>, the program will ask you to select a framework. Choose the one labeled **ESP-IDF**, preferably the latest stable version.

![comm-palette](images\command-palette.png)

In the input field that appears, type:

```
ESP-IDF: New Project
```

After pressing <kbd>Enter</kbd>, a new tab will appear in the program workspace, as shown in the figure below.

![create-proj](images\create-project.png)

In this tab, select the following items from the list:

```
ESP-IDF Examples -> get-started -> blink
```

Then click the **Create project using template blink** button.

## Project Configuration

To configure the project:

1. Open the **Command Palette**.
2. Enter the following command and press <kbd>Enter</kbd>:
```
ESP-IDF: Set Espressif device target
```

3. Select the microcontroller model being used (in our case **ESP32S3**) and then choose the **OpenOCD** download method.
4. Connect the microcontroller to the computer.
5. Enter the following command and press <kbd>Enter</kbd>:
```
ESP-IDF: Select Flash Method
```

6. Select the flashing mode from the list.
7. Enter the following command and press <kbd>Enter</kbd>:
```
ESP-IDF: Select Port to Use
```

8. Select the COM port of the microcontroller.

## Building the Project

To build the project, enter the following command and press <kbd>Enter</kbd>:

```
ESP-IDF: Build Project
```

## Flashing the Project to the ESP32

To flash the project to the **ESP32** microcontroller, enter the following command and press <kbd>Enter</kbd>:

```
ESP-IDF: Flash Device
```

## Monitoring the ESP32

To monitor the operation of the **ESP32** microcontroller, enter the following command and press <kbd>Enter</kbd>:

```
ESP-IDF: Monitor Device
```
