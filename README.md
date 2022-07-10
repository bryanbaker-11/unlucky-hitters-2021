# Who were the unluckiest hitters in the 2021 MLB season?
My second project for the Lede Program 2022.

# Goals
- Determine who the unluckiest hitters were based on expected statistics vs. actual statistics.
- Find hitters with a high hard-hit out percentage.
- Check which hitters appears most throughout all metrics.

# Unlucky Hitter's Python Notebook Summary
- First, I used a pybaseball package to import data on every pitch thrown in the 2021 season. I removed spring training and post season data to focus on the regular season numbers. 
- Then, I filtered the dataframe to only include hard-hit balls (95 mph+ exit velocity). I used str.contains to locate hard-hit balls that resulted in outs and used value_counts() to sort by batter ID.

```python
var player = new MPlayer();

player
    .spawn()
    .then(() => player.loadFile("sample.mp3"))
    .then(() => player.play())
    .then(() => Promise.delay(2000))
    .then(() => player.seek(1000))
    .then(() => player.setSpeed(1.5))
    .then(() => Promise.delay(2000))
    .then(() => player.pause())
    .then(() => player.kill());
```
