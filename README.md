# CS350-Emerging-Systems

<b> Summarize the project and what problem it was solving. </b>

This project tasked us to create a prototype of a Smart Thermostat that sends data to server software over Wi-fi. We used the TMP006 temperature sensor to read room temperature through the I2C. We used the side buttons on the TI Board to control the set point temperature as well as simulate the red LED turning on and off to control heat via the GPIO. Finally, we have data being sent and displayed through the UART that reads the room temperature, set point, heat, and seconds since the last display reset. We also created a written report discussing which architecture would be best suitable for the project, which included Texas Instruments, Freescale and Microchip. Furthermore, we created a Task Scheduler to dictate the required functionality of each step on the Texas Instrument Microcontroller. 

<b> What did you do particularly well? </b>

I believe I did very well utilizing incremental development on the project. I used unit tests to check that each functionality was performing as expected and worked on each component one at a time if applicable.

<b> Where could you improve? </b>

I faced some initial trouble converting the UART statements into UART2, particularly the read and write statements. I eventually solved the problem by extensively researching the UART2 documentation, but I feel finding the information quicker in the program documentation is something I can always improve on.

<b> What tools and/or resources are you adding to your support network? </b>

I am adding the I2C, GPIO, and UART2 documentation to my support network. Having this documentation has been critical to solving errors that were evident of outdated code in most of the assignments throughout this course. 

<b>  What skills from this project will be particularly transferable to other projects and/or course work? </b>

Documentation research, unit testing, incremental development, integration testing and acceptance testing were the most prominent skills that were further enhanced upon in this project that can be used for future work.

<b> How did you make this project maintainable, readable, and adaptable? </b>

I used proper naming conventions for my variables and functions so other programmers and users understand my programming better. I also avoided hardcoding so the project is more maintainable . Finally, I used ample in-line comments so the components of my code are able to be adapted better while avoiding potential errors or bugs.
