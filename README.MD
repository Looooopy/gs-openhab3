# GS Openhab 3

Custom setup for openhab 3.

## Wigets

Custom widget library

### Specialized

Here you will find widgets that has dependencies on Thing and/or Binding  

#### Roku Remote

This remote is designed and tested with Roku Streaming stick + but binding statets it will work with a TV aswell but those commands are not mapped in this remote.

#### Dependencies

##### Hardware

- [Roku streaming stick+](https://www.roku.com/products/streaming-stick-plus)

##### Software

- [Openhab 3](https://www.openhab.org/)

- [Roku Openhab Binding](https://www.openhab.org/addons/bindings/roku/)

- [Icon card Widget](#icon-card)

- **Openhab 3 Setup** Create a **Thing** on that Roku binding above, select "A Roku Streaming Media Player".

### Common

The most reusable widgets that has only dependencies to openhab 3.

#### Icon card

[Icon card](/common/gs_icon_card)

This widgets can be used with only a icon and no text, useful when doing my own remote.

It's built like the oh-label-card with a title and footer but its not required.

