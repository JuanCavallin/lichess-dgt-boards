<div id='wrapper' style='text-align: center;'>
    <div style='display: inline-block; vertical-align: middle;'>
        <a href="https://www.digitalgametechnology.com/index.php/products/electronic-boards">
        <img width="128" alt="DGT Logo" src="https://www.digitalgametechnology.com/images/DGT_The_Chess_Innovators.jpg"></a>
        <br/>
    </div>
    <div style='display: inline-block; vertical-align: middle;'>
        <a title="ornicar / AGPL (http://www.gnu.org/licenses/agpl.html)" href="https://lichess.org">
        <img width="110" alt="Lichess Logo" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Lichess_Logo.svg"></a>
        <br/>lichess.org
    </div>
</div>


<!-- [![FVCproductions](https://avatars1.githubusercontent.com/u/4284691?v=3&s=200)](http://fvcproductions.com) -->

# lichess-dgt-boards

> Play on <a hred="https://lichess.org/">Lichess.org</a> using your <a href="https://www.digitalgametechnology.com/index.php/products/electronic-boards">DGT Electronic Board</a> as input. Incoming moves can be played on audio devices or displayed on the screen. This code can easily be adaptaed to play with other boards.


> The program works by connecting to Lichess via the Board API set of APIs, and to the DGT Board by opening a websocket connecting to the free LiveChess 2.2 which is the software DGT developed to broadcast torunaments. When moves are played on the board the program will detect those and send them to Lichess, and moves played on lichess by your opponent will be announced on screen and by audio, and they need to be executed on the board manually. Text to speech is provided by IBM Watson, and several languages are supported.

**Requirements**

- Any DGT Electronic Board including Smart Board, Blue Tooth, USB and Serial Boards. [https://www.digitalgametechnology.com/index.php/products/electronic-boards]
- LiveChess 2.2 Software installed, opened and able to see the board.
[http://www.livechesscloud.com/software/]
- devDependencies
- npm package
- coverage
- slack
- downloads
- gitter chat
- license
- etc.

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2015 © <a href="http://fvcproductions.com" target="_blank">FVCproductions</a>.
