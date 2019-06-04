"# SFE-DesktopClient-pgx" 

# Build and Run instructions...

## Checkout submodule
- git submodule init
- git submodule update

note: submodule is the minuet core.

## Open visual studio solns
note: use visual studio 2013 or higher
- Symphony.sln
- vendor/SFE-Minute-DesktopClient/Minuet.sln

## Build both solns

## To run
- in Minuet.sln goto project Paragon
- right click on this project and select: 'Set as StartUp Project'
- open project properities
- goto Debug tab
- in 'Command line arguments' add following:

C:\Users\{username}\github\SFE-DesktopClient-pgx\vendor\SFE-Minuet-DesktopClient\bin\paragon\paragon.exe /start-app="C:\Users\{username}\github\SFE-DesktopClient-pgx\bin\out\Symphony.pgx" /env=development --enable-media-stream

where c:\Users\{username}\github is your path to where you cloned project.
- hit start button

## Contributing

1. Fork it (<https://github.com/symphonyoss/SFE-DesktopClient-pgx/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Read our [contribution guidelines](.github/CONTRIBUTING.md) and [Community Code of Conduct](https://www.finos.org/code-of-conduct)
4. Commit your changes (`git commit -am 'Add some fooBar'`)
5. Push to the branch (`git push origin feature/fooBar`)
6. Create a new Pull Request

## License

Copyright (c) 2019 Symphony LLC

The code in this repository is distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
