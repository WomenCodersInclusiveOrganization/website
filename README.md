Creating new network or volunteer tiles.
- Copy template folder & paste into its respective folder 
    - (i.e. copy 'network_tile_template' folder and paste into 'networks' folder. rename folder & modify index.html file)
- Use Carlys volunteer card file structure as an example 
- Add folder name to the respective config.js file

### Adding a network
1. Read our Code of Conduct[], does that align with your organization?
2. Make a fork of this repo to your personal github
3. Clone down this repo locally, create a duplicate of `network_tile_template`, move it to the `network` folder and name it in the following format:
`CountryCode_CityName_NameOfOrg`
Please use the [Alpha-2 code][def]
[def]: https://www.iban.com/country-codes
For example `US_SanDiego_WomenCodersIO`

You can do so in bash from the root directory of this repo:

`cp -r /network_tile_template /networks/US_SanDiego_WomenCodersIO`

3. Make a commit, push to your fork
4. Make a Pull Request back to this repo!