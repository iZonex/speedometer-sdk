# Vehicle digital speedometer

TBD

Purpose of this project, create open source framework for creation digital speedometer HMI's.

Technical proposal:

- Communication can be established via WebSocket communication or HTTP2.0
- Serialization can be covered by well known serialization tool what already have specification generation, lightweight and fast.
- Rendering must cover 3D, 2D scenarios.
- Screen must flex for multiple resolutions

## Project target

Main target for this project cover existing issues with speedometer HMI:

- Information messages must be shown only when this messages required

## Add more usefully information about seat belts and airbag safety

- All information seat belts are not fastened

## Remove fuel useless information

- Gas information can be shown only when it's required.
- Gas information shown only on high-way.
- Gas level shown only when vehicle start with lower level of the fuel.
