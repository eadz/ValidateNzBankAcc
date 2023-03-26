# ValidateNzBankAcc

An implementation of the process described on page 15 of an [IRD pdf](
https://www.ird.govt.nz/-/media/project/ir/home/documents/income-tax/withholding-taxes/rwt-nrwt-withholding-tax-certificate/2020-rwt-and-nrwt-certificate-filing-specification.pdf
)

## Installation

Add this line to your application's Gemfile:

    gem 'validate_nz_bank_acc'

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install validate_nz_bank_acc

## Usage

  ValidateNzBankAcc.new(bank_id, branch_id, account_number, suffix).valid?

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## History

This was originaly developed my myself + others at Localist NZ and released under the MIT licence.

## TODO

Update specs from 2012 era syntax

