# Plan and Requirements analysis - H3

The first assessment for this project is a "Requirements analysis documentation" - worth 5%

Description [here](https://nuku.wgtn.ac.nz/courses/18231/pages/plan-and-requirements-analysis?module_item_id=548280).
Submission [here](https://apps.ecs.vuw.ac.nz/submit/ENGR302/Plan_and_requirements_analysis).

# Transipmedence amplifier

The goal of this project is to create a transipmedence amplifier that takes a current as input and turns that into a voltage as output, where the gain is set through software.

The purpose of the amplifier is to turn a very small current output from a photodiode into a voltage reading in the 1V-10V range. This output necessarily has to be paired with a gain value.

## requirements

### 1. Input

1.1 The device shall measure currents in the range of milliamps to nanoamps.

1.2 The sensor input shall be a 50-ohm BNC connector.

1.3 The device shall have a DC Barrel Connector for providing power to the internal components.

1.4 The voltage of this input shall be researched to find the required voltage of the internal components.

### 2. Output

2.1 The output of the device shall be an analogue voltage in the range of 1V to 10V. Optionally, having a sensitivity of 0.1V.

2.2 The device shall output the standard deviation or variance of the reading.

2.3 The device shall output the current gain setting to the user.
This can be either by: a) a physical display like an LCD, b) sent to the user via software, or both of the above.

2.4 The analogue voltage output shall be provided via a 50-ohm BNC connector.

### 3. Gain switching

3.1 The device shall switch gain values for the amplifier without requiring physical interaction.

3.2 The device shall have a microcontroller capable of switching gain values using its addressable I/O as dictated by communication with said microcontroller.

3.3 The microcontroller shall be programmed to recieve basic get() & set() intstructions for communication with the user via a terminal.

### 4. Usage considerations

4.1 The amplifier will need to be used in a low light environment. This means:

4.1.1 There shall be no sources of light in the design that are not entirely disabled, or disablable, during use.

4.1.2 Any uncovered materials shall be as non-reflective as possible.


### 5. Physical Dimensions

5.1 The device shall fit on a lab desk and be liftable with one hand.

## Plan
Do the Stuff.


### Testing



