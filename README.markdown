# pis_pasep_validator

PIS/PASEP validation for ActiveModel

## Installation

    gem "pis_pasep_validator"

## Usage

    class Person < ActiveRecord::Base
      validates :pis, :pis_pasep => true
    end

## License

Copyright (c) 2012 nohup brasil, released under the MIT license
