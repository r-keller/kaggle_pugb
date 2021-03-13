# Kaggle PUGB Competition

Kaggle released a dataset of over 65,000 games' worth of anonymized data points consisting of number of kills, distance traveled and so on, along with the victory ranking for the match. The question was: What's the best strategy to win in PUGB?

PUGB is a battle royale game where many players (up to 100) are parachuted onto an island to fight or hide until one (or one team) is the last standing. To keep the game interesting, a shrinking bubble is routinely placed on the map so that those outside it will die, forcing players to face each other.


## Motivation

Battle royale games are (a) AWESOME for a quick fix and (b) massively popular outside of just, you know, me :)! PUGB, Fortnite, Apex Legends are just a few to name. Millions and millions of dollars have been spent on battle royale games. But don't just take it from me, check out some spending analysis here: https://www.statista.com/statistics/1078797/battle-royale-in-game-spending-usa-by-game/. In 2020 alone, players spent $ 1.6billion on PUGB and $293 million on Fortnite. Further, almost 350 million people in May 2020 were registered users (https://www.statista.com/statistics/746230/fortnite-players/) of Fortnite worldwide -- that's about the population of the United States, y'all!


## Description of Data

               name       type
                ----       ----
                  Id      object
             groupId      object
             matchId      object
             assists       int64
              boosts       int64
         damageDealt     float64
               DBNOs       int64
       headshotKills       int64
               heals       int64
           killPlace       int64
          killPoints       int64
               kills       int64
         killStreaks       int64
         longestKill     float64
       matchDuration       int64
           matchType      object
            maxPlace       int64
           numGroups       int64
          rankPoints       int64
             revives       int64
        rideDistance     float64
           roadKills       int64
        swimDistance     float64
           teamKills       int64
     vehicleDestroys       int64
        walkDistance     float64
     weaponsAcquired       int64
           winPoints       int64
        winPlacePerc     float64