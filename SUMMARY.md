# Summary

## Summary

* [Introduction](README.md)
* [Licenses](/licenses.md#licenses)
* [Hello World](/hello-world.md)
  * [Compile and Run Hello World](hello-world/compile-and-run-hello-world.md)
  * [Some more fun with Hello World](hello-world/some-more-fun-with-hello-world.md)
* [Walkers, Squares, Indexes](/walkers-squares-indexes.md)
  * [Sides and Squares](walkers-squares-indexes/sides-and-squares.md)
  * [Indices](walkers-squares-indexes/indices.md)
* [Programming](programming.md)
  * [Simplified scheduling](assets/51-simplified-scheduling.md)
  * [Recommended basic programming workflow](assets/52-recommended-basic-programming-workflow.md)
* [Compiling, uploading and erasing scripts](compiling-uploading-scripts.md)
  * [Starting scripts in the standard way](compiling-uploading-scripts/starting-scripts-in-the-standard-way.md)
  * [Multiple script support - from FW 4.5 and RFC 0.8](compiling-uploading-scripts/multiple-script-support-from-fw-45-and-rfc-08.md)
  * [Starting scripts automatically](compiling-uploading-scripts/starting-scripts-automatically.md)
  * [Erasing scripts](compiling-uploading-scripts/erasing-scripts.md)
* [Pawn specialities](pawn-specialties.md)
  * [Default parameters](pawn-specialties/default-parameters.md)
  * [Operator sizeof](pawn-specialties/operator-sizeof.md)
  * [Sizeof from multi-dimension arrays](pawn-specialties/sizeof-from-multi-dimension-arrays.md)
  * [Packed and unpacked](pawn-specialties/packed-and-unpacked-strings.md)
  * [Differences between C and PAWN](pawn-specialties/differences-between-c-and-pawn.md)
* [Colors, palettes and drawing](colors-palettes-and-drawing.md)
* [PWM steps - 64 versus 256](pwm-steps-64-versus-256.md)
* [Push Pop Arrays](push-pop-arrays.md)
* [Default settings for scripts](default-settings-for-scripts.md)
* [Variables](variables.md)
* [Timers](timers.md)
* [Basic commands](basic-commands-to-start-with.md)
* [Interactive shell](interactive-shell.md)
  * [Default shell settings](interactive-shell/default-shell-settings.md)
  * [Shell in RFC Suite](interactive-shell/shell-in-rfc-suite.md)
  * [Accessing shell any time](interactive-shell/configuring-shell.md)
  * [System shell commands](interactive-shell/system-shell-commands.md)
    * [sn](interactive-shell/system-shell-commands/sn.md)
    * [ver](interactive-shell/system-shell-commands/ver.md)
    * [stdshell](interactive-shell/system-shell-commands/stdshell.md)
    * [stdshellnk](interactive-shell/system-shell-commands/stdshellnk.md)
    * [echoon](interactive-shell/system-shell-commands/echoon.md)
    * [echooff](interactive-shell/system-shell-commands/echooff.md)
    * [prompton](interactive-shell/system-shell-commands/prompton.md)
    * [promptoff](interactive-shell/system-shell-commands/promptoff.md)
    * [boot](interactive-shell/system-shell-commands/boot.md)
    * [restart](interactive-shell/system-shell-commands/restart.md)
    * [appinfo](interactive-shell/system-shell-commands/appinfo.md)
    * [fwident\(r\)](interactive-shell/system-shell-commands/fwidentr.md)
    * [cpuident](interactive-shell/system-shell-commands/cpuident.md)
    * [bident](interactive-shell/system-shell-commands/bident.md)
    * [protection](interactive-shell/system-shell-commands/protection.md)
    * [isprotected](interactive-shell/system-shell-commands/isprotected.md)
    * [stackinfo](interactive-shell/system-shell-commands/stackinfo.md)
    * [getms](interactive-shell/system-shell-commands/getms.md)
    * [setms](interactive-shell/system-shell-commands/setms.md)
  * [Video shell commands](interactive-shell/video-shell-commands.md)
    * [iic](interactive-shell/video-shell-commands/iic.md)
    * [clr](interactive-shell/video-shell-commands/clr.md)
    * [pled](interactive-shell/video-shell-commands/pled.md)
    * [pleds](interactive-shell/video-shell-commands/pleds.md)
  * [pledarr](interactive-shell/pledarr.md)
  * [appinfo](interactive-shell/appinfo.md)
  * [play](interactive-shell/play.md)
  * [dir](interactive-shell/dir.md)
  * [q](interactive-shell/q.md)
  * [kill](interactive-shell/kill.md)
  * [tinfo](interactive-shell/tinfo.md)
  * [pdir](interactive-shell/pdir.md)
  * [prun](interactive-shell/prun.md)
  * [prunf](interactive-shell/prunf.md)
  * [prunf N](interactive-shell/prunf_n.md)
  * [prunm](interactive-shell/prunm.md)
  * [pawnerase](interactive-shell/pawnerase.md)
  * [pawneraseflash](interactive-shell/pawneraseflash.md)
  * [pawnerasemycube](interactive-shell/pawnerasemycube.md)
  * [pawn](interactive-shell/pawn.md)
  * [setpawn](interactive-shell/setpawn.md)
  * [setpawnstd](interactive-shell/setpawnstd.md)
  * [setpawnauto](interactive-shell/setpawnauto.md)
  * [pawnmem](interactive-shell/pawnmem.md)
  * [picon](interactive-shell/picon.md)
  * [amxinfo](interactive-shell/amxinfo.md)
  * [var](interactive-shell/var.md)
  * [varpawn](interactive-shell/varpawn.md)
  * [varload](interactive-shell/varload.md)
* [Shell cmd ”motion”](shell-cmd-motion.md)
* [API-Native functions](api-native-functions.md)
  * Graphics
    * ClearVirtualDisplay
    * PrintVirtualDisplay
    * SetPointShine
    * SetPointColor
    * [DrawPoint](api-native-functions/drawpoint.md)
    * [DrawSide](api-native-functions/drawside.md)
    * [SetRgbColor\(r,g,b\)](api-native-functions/setrgbcolorrgb.md)
    * [DrawSquare](api-native-functions/drawsquare.md)
    * [DrawCross](api-native-functions/drawcross.md)
    * [PushCanvas](api-native-functions/pushcanvas.md)
    * [PopCanvas](api-native-functions/popcanvas.md)
    * StoreCanvas
    * LoadCanvas
    * DrawCanvas
    * [PrintCnv](api-native-functions/printcnv.md)
    * [SetDrawDefaults](api-native-functions/setdrawdefaults.md)
    * [SetDrawStyle](api-native-functions/setdrawstyle.md)
    * SetPColor
    * [FlashCanvas](api-native-functions/flashcanvas.md)
    * [DrawFlicker](api-native-functions/drawflicker.md)
    * [DrawCube](api-native-functions/drawcube.md)
    * [AdjCanvasPoint](api-native-functions/adjcanvaspoint.md)
    * [AdjCanvas](api-native-functions/adjcanvas.md)
    * [AdjArray](api-native-functions/adjarray.md)
    * [ReadCanvas](api-native-functions/readcanvas.md)
    * [ReadRGBLed](api-native-functions/readrgbled.md)
    * [ClearCube](api-native-functions/clearcube.md)
    * [DrawPC](api-native-functions/drawpc.md)
    * [PaletteFromArray](api-native-functions/palettefromarray.md)
    * [DrawTail](api-native-functions/drawtail.md)
    * RotateCanvasRGB
  * [Motion](api-native-functions/motion.md)
    * [Motion pattern type list definition](api-native-functions/motion-pattern-type-list-definition.md)
    * [RegMotion](api-native-functions/regmotion.md)
    * ReadMotion
    * [AckMotion](api-native-functions/ackmotion.md)
    * [RegAllSideTaps](api-native-functions/regallsidetaps.md)
    * [UnregMotion](api-native-functions/unregmotion.md)
    * [UnregAllMotion](api-native-functions/unregallmotion.md)
    * GetKickSide
    * KickToWhere
    * [IsStill](api-native-functions/isstill.md)
    * [GetShake](api-native-functions/getshake.md)
    * [RegAllTaps](api-native-functions/regalltaps.md)
    * TapToSide
    * TapToTop
    * TapToBot
    * TapSide
    * TapSideOK
    * [SetDoubleTapLength](api-native-functions/setdoubletaplength.md)
    * Sqrt
    * Get2DPointsDistance
    * Get3DPointsDistance
    * ProjectAccToCube
    * Map3DPointToCube2D
    * Map3DLineToCube2D
    * CalcDistance2DPointTo2DLine
    * CalcSurfaceDistance3DPointTo3DLine
    * CalcSurfaceDistanceAccTo3DLine
    * MapSideSquareTo3DPoint
  * Walkers
    * [WalkerMove](api-native-functions/walkermove.md)
    * [WalkerTurn](api-native-functions/walkerturn.md)
    * [WalkerDiff](api-native-functions/walkerdiff.md)
    * [OppositeStep](api-native-functions/oppositestep.md)
    * GetCsPoint
    * Kick\_Walker
    * Diff\_To\_Spot\_Step
    * [WalkerGetDir](api-native-functions/walkergetdir.md)
    * [WalkerSetDir](api-native-functions/walkersetdir.md)
    * [WalkerGetNorm](api-native-functions/walkergetnorm.md)
    * [WalkerBuddy](api-native-functions/walkerbuddy.md)
    * [WalkerDirUp](api-native-functions/walkerdirup.md)
    * [WalkerCompareDir](api-native-functions/walkercomparedir.md)
    * [Walker Init / \_w](api-native-functions/w.md)
  * Scores
    * [Score Definition](api-native-functions/score-definition.md)
    * SetScore
    * SetAP
    * GetAP
    * GetPS
    * AnnounceBestScore
  * Precise Timing
    * EnablePreciseTiming
    * TimerIncSet
    * TimerIncGet
    * SetAppMsec
  * Sound
    * [Play](api-native-functions/play.md)
    * [SetAudioForce](api-native-functions/setaudioforce.md)
    * [SetVolume](api-native-functions/setvolume.md)
    * [Melody](api-native-functions/melody.md)
    * [WaitPlayOver](api-native-functions/waitplayover.md)
    * [WaitMelodyOver](api-native-functions/waitmelodyover.md)
    * [Quiet](api-native-functions/quiet.md)
    * [IsPlayOver](api-native-functions/isplayover.md)
    * [IsMelodyOver](api-native-functions/ismelodyover.md)
    * PlayAtCh
    * SetChVolume
    * IsPlayAtChOver
    * StopPlayAtCh
    * MountFolder
    * GetNumberOfFiles
    * PlayNthFileAtCh
    * FFTOn
    * FFTOff
    * GetFFTCoeff
  * Radio
    * RadioInit
    * RadioMessage
    * RadioMsgWritable
    * RadioMsgReadable
    * RadioMsgWrite
    * RadioMsgRead
    * RadioGetOrder
    * RadioGetSessionID
    * RadioIsLost
    * RadioSetDelays
    * RadioSetBinary
    * BleConnected
    * BleSmartTx
    * BleDataTx
    * BleDataAvailable
    * BleDataRx
    * GetPreciseUsTimer
    * ClearPreciseUsTimer
    * BleFlush
    * BleTextTx
  * Misc
    * [Sleep](api-native-functions/sleep.md)
    * [Delay](api-native-functions/delay.md)
    * [SetTimer](api-native-functions/settimer.md)
    * [GetTimer](api-native-functions/gettimer.md)
    * [PauseTimer](api-native-functions/pausetimer.md)
    * [ResumeTimer](api-native-functions/resumetimer.md)
    * [printf](api-native-functions/printf.md)
    * [snprintf](api-native-functions/snprintf.md)
    * [cellset](api-native-functions/cellset.md)
    * [cellcopy](api-native-functions/cellcopy.md)
    * [PushPopInit](api-native-functions/pushpopinit.md)
    * [Push](api-native-functions/push.md)
    * [Pop](api-native-functions/pop.md)
    * [PPReady](api-native-functions/ppready.md)
    * [PPFree](api-native-functions/ppfree.md)
    * [ReadAcc](api-native-functions/readacc.md)
    * [GetCursor](api-native-functions/getcursor.md)
    * [IsGameResetRequest](api-native-functions/isgameresetrequest.md)
    * [Vibrate](api-native-functions/vibrate.md)
    * [CollisionTest](api-native-functions/collisiontest.md)
    * ScanF
    * GetShellMessage
    * GetSystemVoltage
    * IsUsbConnected
    * ReadImu // new API4 IMU
    * [Restart](api-native-functions/restart.md)
    * [GetMsecs](api-native-functions/getmsecs.md)
    * [GetAppMsecs](api-native-functions/getappmsecs.md)
    * [StartGameMenu](api-native-functions/startgamemenu.md)
    * [SetRndSeed](api-native-functions/setrndseed.md)
    * [GetRnd](api-native-functions/getrnd.md)
    * [SetRandomizeFlag](api-native-functions/setrandomizeflag.md)
    * [SetStillClick](api-native-functions/setstillclick.md)
    * AddActiveTime
    * ModsSelect
    * Pawn\_Score
    * Announce\_Score
    * [DrawDigit](api-native-functions/drawdigit.md)
    * [Icon](api-native-functions/icon.md)
    * [PrintArray](api-native-functions/printarray.md)
    * [VariableMagics](api-native-functions/variablemagics.md)
    * [RegisterVariable](api-native-functions/registervariable.md)
    * [StoreVariable](api-native-functions/storevariable.md)
    * [LoadVariable](api-native-functions/loadvariable.md)
    * [ApiVer](api-native-functions/apiver.md)
    * Shell
    * [Useful Macros](api-native-functions/usefulmacros.md)
    * [Macros Examples](api-native-functions/macro-examples.md)
    * [ClearCanvas](api-native-functions/clearcanvas.md)
    * [PrintCanvas](api-native-functions/printcanvas.md)
    * [SetIntensity](api-native-functions/setintensity.md)
    * [SetColor](api-native-functions/setcolor.md)
    * [Preset color definition](api-native-functions/preset-color-definition.md)
    * [Basic color definition](api-native-functions/basic-color-definition.md)
    * [CanvasToArray](api-native-functions/canvastoarray.md)
    * [ArrayToCanvas](api-native-functions/arraytocanvas.md)
    * [DrawArray](api-native-functions/drawarray.md)
    * [Drawing style definition](api-native-functions/drawing-style-definition.md)
    * [SetPalette](api-native-functions/setpalette.md)
    * [Flicker type definition](api-native-functions/flicker-type-definition.md)
    * [GetTapSide](api-native-functions/gettapside.md)
    * [GetTapType](api-native-functions/gettaptype.md)
    * [Easy Tap Type Detection](api-native-functions/easy-tap-type-detection.md)
    * [STEP definition](api-native-functions/step-definition.md)
    * [TURNS definition](api-native-functions/turns-definition.md)
    * [WalkerStepTo](api-native-functions/walkerstepto.md)
    * [GetSymmetrySquare](api-native-functions/getsymmetrysquare.md)
    * [WalkerTap](api-native-functions/walkertap.md)
    * [Score](api-native-functions/score.md)
    * [DrawScore](api-native-functions/drawscore.md)
* [Release notes](release-notes.md)
  * [SDK manual](release-notes/sdk-manual.md)
  * [futurocube.inc](release-notes/futurocubeinc.md)
* [Examples](examples.md)
  * [Cursor](examples/cursor.md)
  * [Tapping](examples/tapping.md)
  * [Walker](examples/walker.md)
  * [Paint My Cube](examples/paint-my-cube.md)
  * [Animated Rubiks Cube](examples/animated-rubiks.md)
  * [Disco Cube](examples/disco-cube.md)
  * [Motion](examples/motion.md)
  * [Defuser](examples/defuser.md)
  * [SScanf](examples/sscanf.md)
  * [Music Player](examples/music-player.md)
* [Sound resources](sound-resources.md)
  * [Uploading resources](sound-resources/uploading-resources.md)
  * [Erasing resources](sound-resources/erasing-resources.md)
  * [Playback priorities](sound-resources/playback-priorities.md)
  * [Naming conventions](sound-resources/naming-conventions.md)
  * [Sample rate compensation](sound-resources/sample-rate-compensation.md)
  * [Frequency response compensation](sound-resources/frequency-response-compensation.md)
* [Installation packages](installation-package.md)
* [Bluetooth Low Energy - **EXPERIMENTAL**](ble.md)
  * [SW requirements](ble/sw-reqs.md)
  * [HW setup](ble/hw-setup.md)
  * [BLE characteristic offered by Rubik’s Futuro Cube](ble/ble-characteristics.md)
  * [USB dongle](ble/usb-dongle.md)
  * [Dongle commands on CONTROL line](ble/dongle-commands.md)
  * [Asynchronous messages on CONTROL line](ble/async-messages.md)
  * [Important Cube SHELL commands](ble/important-shell-commands.md)
  * [Python SDK](ble/python-sdk.md)
  * [Ble Dongle Terminal](ble/-ble-dongle-terminal.md)
  * [Limitations and Properties](ble/limitations-and-properties.md)
  * [HW details about dongle serial communication](ble/dongle-serial-connection.md)
  * [2-Way Communication With Running Script](ble/-running-script-communication.md)
  * [Changes in Ble Dongle Terminal](ble/changes-in-ble-terminal.md)
  * [First 2 Way Test With Provided Example](ble/first-two-way-test.md)
  * [Useful Hints](ble/useful-hints.md)
  * [Priorities of Queues](ble/priorities-of-queues.md)