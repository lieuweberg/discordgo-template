# discordgo-template
A [discordgo](https://github.com/bwmarrin/discordgo) template for simple bots. Got tired of writing the same thing over and over again.

## Usage
1. Clone this project
   ```sh
   git clone https://github.com/lieuweberg/discordgo-template.git
   ```
2. Optionally you can find & replace all instances of `github.com/lieuweberg/discordgo-template` with your own project's url (e.g. `github.com/myname/mycoolbot`).
3. Rename `config-example.json` to `config.json` and fill in the bot token.
4. Run the bot
   ```sh
   go run main.go
   ```

This bot comes with one command: ping. The prefix can be changed above the messageCreate function and is by default `bot `, so try if everything works with `bot ping`. You can copy the commands/ping.go file and use that as a command template. Mind you that this is all very basic and just a quick start template.

## Credit & License
This project uses the MIT license. Licensed works, modifications, and larger works may be distributed under different terms and without source code. However, credit to this project is always appreciated :)
