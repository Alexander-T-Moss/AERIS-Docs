---
hide:
  - footer
  - navigation
---

# Alternatives

There is already several excellent air quality monitors similar to AERIS. If you’re unsure if AERIS is best suited for you and want to see how it compares to other options, this section provides helpful context.

## AERIS (Made By Me)

[AERIS](https://github.com/Alexander-T-Moss/Aeris) stands as a budget and DIY-friendly alternative to existing air quality monitors. Many choices, including hardware selection and device interaction, have been made with a focus on making [AERIS](https://github.com/Alexander-T-Moss/Aeris) as accessible as possible to DIY enthusiasts.

??? success "Advantages"

    - Relatively inexpensive due to its DIY focused design
    - Accessible for DIY tinkerers to build
    - Open-source design with active development

??? warning "Drawbacks"

    - Project is still in its infancy
    - Not currently an off-the-shelf solution/product

The DIY, open-source-focused design of [AERIS](https://github.com/Alexander-T-Moss/Aeris) is a double-edged sword. While you benefit from cost savings and the option to fully modify every aspect, the lack of an off-the-shelf product (for now) may be a barrier for some.

## AIR-1 (Apollo Automation)

[AIR-1](https://apolloautomation.com/products/air-1) by [Apollo Automation](https://apolloautomation.com/) is an off-the-shelf, ESPHome powered air quality monitor. It uses a combination of the SEN55, SCD40, and MiCS-4514 sensors to record a wide range of parameters from its surrounding environment.

??? success "Advantages"

    - Wide sensor array, covering all the parameters you'd realistically need  
    - Compact form factor, the smallest monitor in its class  
    - Well-reviewed and produced by an established IoT creator

??? warning "Drawbacks"

    - Requires Home Assistant or Homey hub to view data readings  
    - Relatively expensive  
    - Closed-source design (although some source files are provided)

The [AIR-1](https://apolloautomation.com/products/air-1) is a solid off-the-shelf solution. However, development on this project appears to have slowed, and the requirement of a smart home hub to utilise the unit may pose as a roadblock.

## Airgradient One (Airgradient)

[AirGradient ONE](https://www.airgradient.com/) by [AirGradient](https://www.airgradient.com/) is an open-source indoor air quality monitor designed for accuracy and large scale deployment. It integrates seamlessly with AirGradient’s bespoke dashboard for real-time monitoring.

??? success "Advantages"

    - Powerful dashboard integration
    - Open source design
    - Comes with certifications and warranty

??? warning "Drawbacks"

    - Relatively expensive

Airgradient have created a powerful bespoke dashboard to monitor several of their air quality monitors, however the higher cost of these devices maybe off-putting to DIY tinkerers, and many of the unique features (like certifications) are geared to a more enterprise environment.

## Sensorbox v2 (Made With Layers)

[Sensorbox v2](https://www.printables.com/model/1079858) by [Made With Layers](https://www.youtube.com/channel/UCb8Rde3uRL1ohROUVg46h1A) (Thomas Sanladerer) is a popular air quality monitor positioned primarily for tracking the emissions of 3D printers.

??? success "Advantages"

    - Wide range of supported hardware
    - Popular design

??? warning "Drawbacks"

    - Requires Home Assistant to fully utilize
    - Lacks comprehensive documentation and project development appears to have stalled
    - Some recommended sensors have inconsistent accuracy

[Sensorbox v2](https://www.printables.com/model/1079858) is an excellent DIY project as a jack of all trades rather than a master of a few. However some users may be put off by the lack of documentation for this project.

*[ESPHome]: Home Assistant add-on for creating custom firmware for IoT devices 
*[Home Assistant]: Software platform for centralized home automation