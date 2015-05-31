# Time
1 Game turn (1 minute) == 6 Combat rounds

1 Combat round (10 seconds) == 10 Phases

1 Phase (1 second) == 1 Action

## Active phases
Initiative / 10 (rounding down) gives number of actions per round.

Actions in the same phase are simultaneous with the lowest initiative declaring first.

Actions occur in the following phases:

<table>
  <thead>
    <tr>
      <th rowspan="2" scope="col">No of actions</th>
      <th colspan="10">Phase</th>
    </tr>
    <tr>
      <th scope="col">1</th>
      <th scope="col">2</th>
      <th scope="col">3</th>
      <th scope="col">4</th>
      <th scope="col">5</th>
      <th scope="col">6</th>
      <th scope="col">7</th>
      <th scope="col">8</th>
      <th scope="col">1</th>
      <th scope="col">10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td data-phase="1">-</td>
      <td data-phase="2">-</td>
      <td data-phase="3">-</td>
      <td data-phase="4">-</td>
      <td data-phase="5">-</td>
      <td data-phase="6">X</td>
      <td data-phase="7">-</td>
      <td data-phase="8">-</td>
      <td data-phase="9">-</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td data-phase="1">-</td>
      <td data-phase="2">-</td>
      <td data-phase="3">-</td>
      <td data-phase="4">X</td>
      <td data-phase="5">-</td>
      <td data-phase="6">-</td>
      <td data-phase="7">X</td>
      <td data-phase="8">-</td>
      <td data-phase="9">-</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td data-phase="1">-</td>
      <td data-phase="2">-</td>
      <td data-phase="3">X</td>
      <td data-phase="4">-</td>
      <td data-phase="5">-</td>
      <td data-phase="6">X</td>
      <td data-phase="7">-</td>
      <td data-phase="8">-</td>
      <td data-phase="9">X</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">4</th>
      <td data-phase="1">-</td>
      <td data-phase="2">X</td>
      <td data-phase="3">-</td>
      <td data-phase="4">X</td>
      <td data-phase="5">-</td>
      <td data-phase="6">X</td>
      <td data-phase="7">-</td>
      <td data-phase="8">X</td>
      <td data-phase="9">-</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">5</th>
      <td data-phase="1">X</td>
      <td data-phase="2">-</td>
      <td data-phase="3">X</td>
      <td data-phase="4">-</td>
      <td data-phase="5">X</td>
      <td data-phase="6">-</td>
      <td data-phase="7">X</td>
      <td data-phase="8">-</td>
      <td data-phase="9">X</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">6</th>
      <td data-phase="1">X</td>
      <td data-phase="2">X</td>
      <td data-phase="3">-</td>
      <td data-phase="4">X</td>
      <td data-phase="5">-</td>
      <td data-phase="6">X</td>
      <td data-phase="7">-</td>
      <td data-phase="8">X</td>
      <td data-phase="9">-</td>
      <td data-phase="10">X</td>
    </tr>
    <tr>
      <th scope="row">7</th>
      <td data-phase="1">X</td>
      <td data-phase="2">X</td>
      <td data-phase="3">-</td>
      <td data-phase="4">X</td>
      <td data-phase="5">X</td>
      <td data-phase="6">-</td>
      <td data-phase="7">X</td>
      <td data-phase="8">X</td>
      <td data-phase="9">X</td>
      <td data-phase="10">-</td>
    </tr>
    <tr>
      <th scope="row">8</th>
      <td data-phase="1">X</td>
      <td data-phase="2">X</td>
      <td data-phase="3">X</td>
      <td data-phase="4">-</td>
      <td data-phase="5">X</td>
      <td data-phase="6">X</td>
      <td data-phase="7">X</td>
      <td data-phase="8">-</td>
      <td data-phase="9">X</td>
      <td data-phase="10">X</td>
    </tr>
    <tr>
      <th scope="row">9</th>
      <td data-phase="1">X</td>
      <td data-phase="2">X</td>
      <td data-phase="3">X</td>
      <td data-phase="4">X</td>
      <td data-phase="5">X</td>
      <td data-phase="6">-</td>
      <td data-phase="7">X</td>
      <td data-phase="8">X</td>
      <td data-phase="9">X</td>
      <td data-phase="10">X</td>
    </tr>
    <tr>
      <th scope="row">10</th>
      <td data-phase="1">X</td>
      <td data-phase="2">X</td>
      <td data-phase="3">X</td>
      <td data-phase="4">X</td>
      <td data-phase="5">X</td>
      <td data-phase="6">X</td>
      <td data-phase="7">X</td>
      <td data-phase="8">X</td>
      <td data-phase="9">X</td>
      <td data-phase="10">X</td>
    </tr>
  </tbody>
</table>

## Actions
Sample actions:

 * Move - up to four per round
    * walk 2m
    * run 4m
    * jump 2m vertical, 4m vertical (+1m for up to 4 run actions)
    * 1m climb
    * 2m swim
 * Stand, sit, fall down, crouch
 * Speak - 20 words + (2 x actions per round) free per round
 * Listen/observe
 * Open/close item
 * Pick up or use object
 * Aim
 * Fire
 * Reload (2 actions)
 * Strike a blow
 * Enter or leave a vehicle
 * Drive - must spend one action per round to maintain control of a moving vehicle
 * Halt a vehicle
