# Shoot Run

"Shoot Run" is a fun terminal-based shooting game that revolves around a shooter tasked with eliminating zombies.

The shooter has a health level, symbolized by blood. With each zombie attack, the shooter’s health diminishes. If his health runs out, he transforms into a zombie himself then game over.

The game features a moving portal in each room, which the shooter can use to escape. Note that, the more zombies the shooter eliminates, the more zombies become aware of his presence, leading to an increase in the number of zombies in the game.

![Screenshot](https://i.imgur.com/dHRmrh1.gif)

## Play

### Docker

Should execute it with `-it flag`:

```bash
docker run -it --rm --name shoot-run kadsin/shoot-run
```

### Locally

Go version: `1.21.3`

```bash
make run
```

#### Compile (To the `bin` directory)

```bash
make compile
```

## Running the tests

```bash
make tests
```

## Contributing

Feel free to create any pull request you want to improve the game.
