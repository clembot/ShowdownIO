# Showdown I/O
Showdown I/O is a Python-Selenium-based interface for autonomous battle monitoring and play on Pokémon Showdown. With it, you can automatically participate in or just collect information about battles happening on the world's most popular Pokémon battle simulator. 

---

Showdown I/O offers a simple yet powerful interface for automating play on Pokémon Showdown, only but comprehensively exposing objects or actions a developer might need for implementing a battle bot. Battle states are represented as structured dictionaries encodable into JSON format while actions can be submitted efficiently and coherently. Supported actions include:
- Logging in as a specified user
- Collecting maximally comprehensive representations of any battle's current state and history
- Starting and ending battles on a selected ladder or with a specific user
- Playing through battles by submitting decisions and monitoring their consequences for the battle state

The Selenium-based approached embraced by Showdown I/O is just one of many possible ways to implement a Pokémon Showdown API for battling bots. An alternative is the [Socket Battle Bot for Pokemon Showdown](https://github.com/Synedh/showdown-battle-bot), which relies on the [Pokémon Showdown Battle Protocol](https://github.com/Zarel/Pokemon-Showdown/blob/master/PROTOCOL.md) to interface with servers. Selenium is arguably clunkier but is favored here for its familiarity to developers and transparency for potential clients. 

## Installation

## Usage

## Credits
