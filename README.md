# WAPI.github.io
toots


<html>
  <body>
    <button id="start-button">Start Loop</button>
    <button id="stop-button">Stop Loop</button><br>
    <label for="volume-control">Master Volume</label><br>
    <input type="range" id="volume-control" min="0" max="1" step="0.05" value=".2"><br>
    <label for="tempo-control">Tempo</label><br>
    <input type="range" id="tempo-control" min="60" max="300" step="5" value="120"><br>
    <div id="note-selects-div">
      <h2>Notes</h2>
    </div>
    <div id="oscillator-options">
      <h2>Oscillator</h2>
      <input type="radio" id="sin-wave" name="waveform" value="sine"
      checked>
      <label for="sin-wave">Sin Wave</label><br>
      <input type="radio" id="square-wave" name="waveform" value="square">
      <label for="square-wave">Square Wave</label><br>
      <input type="radio" id="triangle-wave" name="waveform" value="triangle">
      <label for="triangle-wave">Triangle Wave</label><br>
      <input type="radio" id="sawtooth-wave" name="waveform" value="sawtooth">
      <label for="sawtooth-wave">Sawtooth Wave</label>
    </div>
    <div id="envelope-options">
      <h2>Envelope</h2>
      <label for="attack-control">Attack Time</label><br>
      <input type="range" id="attack-control" value="0.3" min="0" max="0.5" step="0.02"><br>
      <label for="release-control">Release Time</label><br>
      <input type="range" id="release-control" value="0.3" min="0" max="0.5" step="0.02"><br>
      <label for="note-length-control">Note Length</label><br>
      <input type="range" id="note-length-control" value="1" min="0.2" max="2" step="0.05"><br>
    </div>
    <div id="vibrato-options">
      <h2>Vibrato</h2>
      <label for="vibrato-amount-control">Vibrato Amount</label><br>
      <input type="range" id="vibrato-amount-control" value="0" min="0" max="5" step="0.5"><br>
      <label for="vibrato-amount-control">Vibrato Speed</label><br>
      <input type="range" id="vibrato-speed-control" value="10" min="0" max="30" step="0.5"><br>
    </div>
    <div id="delay-options">
      <h2>Delay</h2>
      <label for="delay-time-control">Delay Time</label><br>
      <input id='delay-time-control' type="range" min = "0" max = "1" step='0.05' value='0'><br>
      <label for="feedback-control">Delay Feedback</label><br>
      <input id='feedback-control' type="range" min = "0" max = ".9" step='0.05' value='0'><br>
      <label for="delay-amount-control">Delay Amount</label><br>
      <input id='delay-amount-control' type="range" min = "0" max = ".9" step='0.05' value='0'>
    </div>
  </body>
</html>
