# Pokemon Mystery Dungeon dataset
Pokemon Mystery Dungeon dataset with locations, recruit rates and friend areas. It has data from:
 
+ Red Rescue Team / Blue Rescue Team
+ Explorers of Sky

I scraped all the info from [bulbapedia](https://bulbapedia.bulbagarden.net). My jupyter notebook is available.
This repository has both the CSV and JSON files.

Here's what it looks like:

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>name</th>
      <th>rt_location</th>
      <th>rt_rate</th>
      <th>friend_area</th>
      <th>sky_location</th>
      <th>sky_rate</th>
      <th>picture</th>
    </tr>
    <tr>
      <th>pokedex_number</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>Bulbasaur</td>
      <td>Starter Pokémon, Partner Pokémon, Joyous Tower...</td>
      <td>12.5%</td>
      <td>Beau Plains</td>
      <td>Starter Pokémon, Partner Pokémon, Mystifying F...</td>
      <td>8.2%</td>
      <td>//archives.bulbagarden.net/media/upload/f/fa/M...</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Ivysaur</td>
      <td>Western Cave(B19F-B27F)</td>
      <td>-19%</td>
      <td>Beau Plains</td>
      <td>Mystifying Forest(B1-B13), Sky Peak(1st Statio...</td>
      <td>-10%</td>
      <td>//archives.bulbagarden.net/media/upload/3/34/M...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Venusaur</td>
      <td>Evolve, Ivysaur</td>
      <td>Evolve</td>
      <td>Beau Plains</td>
      <td>Mystery Jungle(1F-29F)</td>
      <td>-12%</td>
      <td>//archives.bulbagarden.net/media/upload/8/8c/M...</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Charmander</td>
      <td>Starter Pokémon, Partner Pokémon, Fiery Field(...</td>
      <td>11.7%</td>
      <td>Mt. Cleft</td>
      <td>Starter Pokémon, Partner Pokémon, Dark Crater(...</td>
      <td>8.2%</td>
      <td>//archives.bulbagarden.net/media/upload/1/17/M...</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Charmeleon</td>
      <td>Fiery Field(26F-29F)</td>
      <td>-19%</td>
      <td>Mt. Cleft</td>
      <td>Giant Volcano(1F-19F), Dark Crater(B1F-B15F, D...</td>
      <td>-10%</td>
      <td>//archives.bulbagarden.net/media/upload/d/d2/M...</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>488</th>
      <td>Cresselia</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Sharpedo Bluff</td>
      <td>100%</td>
      <td>//archives.bulbagarden.net/media/upload/c/c5/M...</td>
    </tr>
    <tr>
      <th>489</th>
      <td>Phione</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Miracle Sea(Bottom)</td>
      <td>100%</td>
      <td>//archives.bulbagarden.net/media/upload/c/cc/M...</td>
    </tr>
    <tr>
      <th>490</th>
      <td>Manaphy</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Sharpedo Bluff(after finding, Wonder Eggin, Su...</td>
      <td>100%</td>
      <td>//archives.bulbagarden.net/media/upload/5/5d/M...</td>
    </tr>
    <tr>
      <th>491</th>
      <td>Darkrai</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Mystifying Forest(13F), Lower Crevice Cave(B2F...</td>
      <td>-22%</td>
      <td>//archives.bulbagarden.net/media/upload/f/f9/M...</td>
    </tr>
    <tr>
      <th>492</th>
      <td>Shaymin</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Sky Peak (Top)</td>
      <td>100%</td>
      <td>//archives.bulbagarden.net/media/upload/c/cd/M...</td>
    </tr>
  </tbody>
</table>
<p>492 rows × 7 columns</p>
</div>
