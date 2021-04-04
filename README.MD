# GS Openhab 3

Custom setup for openhab 3.

## Wigets

Custom widget library

### Specialized

Widgets that has dependencies on Thing and/or Binding, this repository, [openhab-webui components](https://github.com/openhab/openhab-webui/tree/main/bundles/org.openhab.ui/doc/components) and/or on [Framework7](https://framework7.io/).

#### Roku Remote

[Roku remote](/specialized/gs_roku_remote.yaml)

This remote is designed and tested with Roku Streaming stick + but in the [Roku Openhab Binding](https://www.openhab.org/addons/bindings/roku/) they state it will work with a TV as well but those commands are not mapped in this remote.

#### Dependencies

##### Hardware

- [Roku streaming stick+](https://www.roku.com/products/streaming-stick-plus)

##### Software

- [Openhab 3](https://www.openhab.org/)

- [Roku Openhab Binding](https://www.openhab.org/addons/bindings/roku/)

- [Icon card Widget](#icon-card)

- **Openhab 3 Setup** Create a **Thing** on that Roku binding above, select "A Roku Streaming Media Player".

### Common

Widgets that has dependencies only to openhab 3 or [Framework7](https://framework7.io/) that [openhab-webui](https://github.com/openhab/openhab-webui) utilizes.

#### Icon card

[Icon card](/common/gs_icon_card.yaml)

This widgets can be used with only a icon and no text, useful when doing a remote.

It's built like the oh-label-card with a title and footer but its not required.

