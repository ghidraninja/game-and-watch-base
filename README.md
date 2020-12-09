# game-and-watch-base
Base project for Game &amp; Watch firmware.

You will need to have the Drivers in the `game-and-watch-base` directory for the `Makefile` to complete successfully, 
otherwise you will get an error about the `stm32h7xx_hal.o` file being missing. Since we already have these files in another directory, 
we can simply create a symbolic link to them using the following command wich will result in a successful build.:

`ln -s ../game-and-watch-retro-go/STM32CubeH7/Drivers Drivers`

