# Amqp::Sub

AMQP topic subscribe tool

## Installation

    $ git clone <this repository>
    $ cd <repository dir>
    $ rake build
    $ gem install pkg/*.pkg

## Usage

    $ amqp-sub -s <AMQP_SERVER> -t <TOPIC> [-r <ROUTING_KEY>]

## Example

    $ amqp-sub -s `boot2docker ip` -t amq.topic -r tests.#
