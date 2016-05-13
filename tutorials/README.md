# Adding Custom Symbols to PI Coresight 3
## About
This repository is set up to help you learn how to add a custom symbol, created with JavaScript and HTML, to PI Coresight 3, which is currently in beta. You will 'register' a custom symbol to add it to the available 'symbol library' and learn how to access data for the symbol when it is placed on a display. You will also learn how the symbol and application can interact with each other in ways such as responding to time range changes. Finally, you will see how the symbol is persisted with the display and hooked into the undo/redo system.

## Creating new symbols
Each section below is used to walkthrough the creation of a specific custom symbol. It is recommended to go through the simple value symbol instructions first. Each set of instructions is meant to be run as a copy and paste exercise.

* [Simple Value Symbol Instructions](/simplevalue/README.md)
* [TimeSeries Chart Instructions](/timeserieschart/README.md)
* [Liquid Gauge (d3) Instructions](/liquidgauge/README.md)