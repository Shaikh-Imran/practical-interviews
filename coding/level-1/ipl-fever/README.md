For this IPL season, given the URL of the file **ipl-fever-input.txt**, Find the Orange and Purple Cap Player.

**Orange Cap Player** - Player with Most **runs** combined
<br>

**Purple Cap Player** - Player with Most **wickets** combined

## Input

- `ipl-fever-input.txt` file URL. (use GitHub's `Raw` file url)

- Data fields has been split by `|`. And the format is as follows

```
Name of the Player|<Bowler or Batsman>|<no of wickets OR Runs>
```

- if the row contains `Batsman` then the last field represents `Runs`
- if the row contains `Bowler` then the last field represents `Wickets`.
- a player can be appeared as `Batsman` and `Bowler` in the data, But not at the same time.
  - For example, `Pandya`

## Constraint

- You should read the file with the given URL only.
- Keep the code clean and readable
- can use internet
- OOP is preferred

## Output

- Print the orange cap player with his total runs
- Print the purple cap player with his total wickets

<details>
<summary>#### Follow Up questions</summary>

- Print the player with maximum runs in a the single match
- Print the player with maximum wickets in a single match

</details>
