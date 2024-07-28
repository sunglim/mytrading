# My Trading

## Motivation

## Integration with `indicator`

The indicator is a go package providing useful chart indicators like RSI. This project will use indicator as a core package.

### Core logic

- open a channel
- create an indicator.Strategy, pass the channel created
- periodically push data to the channel
- indicator.Strategy returns strategy.Action
- stock order with the action

### Implement

TODO
