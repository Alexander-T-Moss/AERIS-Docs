---
hide:
  - footer
---

# Alternatives

There are already several excellent air quality monitors similar to AERIS. If you’re unsure about AERIS and want to see how it compares to other options, this section provides helpful context.

## AERIS (Made By Me)

[AERIS](https://github.com/Alexander-T-Moss/Aeris) stands as a budget and DIY-friendly alternative to existing products. Many design choices, including hardware selection and device interation, have been made with a focus on making [AERIS](https://github.com/Alexander-T-Moss/Aeris) as accessible as possible to DIY enthusiasts.

??? success "Advantages"

    - Relatively inexpensive due to its DIY nature
    - Accessible for DIY tinkerers to build
    - Open-source design with active development

??? warning "Drawbacks"

    - Project is still in its infancy, so more likely future issues will be uncovered
    - Not currently an off-the-shelf solution/product

The DIY, open-source-focused design of [AERIS](https://github.com/Alexander-T-Moss/Aeris) is a double-edged sword. While you benefit from cost savings and full customization of every aspect, the lack of an off-the-shelf product (for now) may be a barrier for some.

## AIR-1 (Apollo Automation)

[AIR-1](https://apolloautomation.com/products/air-1) by [Apollo Automation](https://apolloautomation.com/) is an off-the-shelf, ESPHome-powered air quality monitor. It uses a combination of the SEN55, SCD40, and MiCS-4514 sensors to record a wide range of parameters from its surrounding environment.

??? success "Advantages"

    - Wide sensor array, covering all the parameters you'd realistically need  
    - Compact form factor, the smallest monitor in its class  
    - Well-reviewed and produced by an established IoT creator

??? warning "Drawbacks"

    - Requires Home Assistant to view data readings  
    - Relatively expensive  
    - Closed-source design (although some source files are provided)

The [AIR-1](https://apolloautomation.com/products/air-1) is a solid off-the-shelf solution. However, development on this project appears to have slowed, and the requirement of a smart home hub to utilise the unit may pose as a roadblock to some.

## Airgradient One (Airgradient)

[AirGradient ONE](https://www.airgradient.com/) by [AirGradient](https://www.airgradient.com/) is an open-source indoor air quality monitor designed for accuracy and large scale deployment. It integrates seamlessly with AirGradient’s bespoke dashboard for real-time monitoring.

??? success "Advantages"

    - Powerful dashboard integration
    - Open source design
    - Comes with certifications and warranty

??? warning "Drawbacks"

    - Relatively expensive

Airgradient have created a powerful bespoke dashboard to monitor several of their air quality monitors, however the higher cost of these devices may pose as a barrier to DIY tinkerers, and many of the unique features are geared to a more enterprise environment

## Sensorbox v2 (Made With Layers)

[Sensorbox v2](https://www.printables.com/model/1079858) by [Made With Layers](https://www.youtube.com/channel/UCb8Rde3uRL1ohROUVg46h1A) (Thomas Sanladerer) is a popular air quality monitor designed primarily for tracking the emissions of 3D printers.

??? success "Advantages"

    - Wide range of supported hardware
    - Popular design

??? warning "Drawbacks"

    - Requires Home Assistant to fully utilize
    - Lacks comprehensive documentation, and project development appears to be stale
    - Some recommended sensors have inconsistent accuracy

Although [Sensorbox v2](https://www.printables.com/model/1079858) is a great DIY project, it comes across trying to be a jack of all trades rather than a master of a few. The lack of documentation and stagnant development may be off-putting to some users.