### Latest Gas Prices

Please ensure that you have updated your gas prices as follows: 

`{"uluna":"28.325","usdr":"0.52469","uusd":"0.75","ukrw":"850.0","umnt":"2142.855","ueur":"0.625","ucny":"4.9","ujpy":"81.85","ugbp":"0.55","uinr":"54.4","ucad":"0.95","uchf":"0.7","uaud":"0.95","usgd":"1.0","uthb":"23.1","usek":"6.25","unok":"6.25","udkk":"4.5","uidr":"10900.0","uphp":"38.0","uhkd":"5.85","umyr":"3.0","utwd":"20.0"}`

### Gas Prices Tracker

Once updated, kindly create a PR to the following files, by changing `not-updated` against your name to `updated`.

Validators: [Create PR here](validators.json)


### How to update gas prices

Please replace in your terrad `app.toml` file the `minimum-gas-prices` variable from:
`minimum-gas-prices = "old values"`
to:
`minimum-gas-prices = "28.325uluna,0.52469usdr,0.75uusd,850.0ukrw,2142.855umnt,0.625ueur,4.9ucny,81.85ujpy,0.55ugbp,54.4uinr,0.95ucad,0.7uchf,0.95uaud,1.0usgd,23.1uthb,6.25usek,6.25unok,4.5udkk,10900.0uidr,38.0uphp,5.85uhkd,3.0umyr,20.0utwd"`

and restart terrad for the changes to take effect.
