This repo contains a simple default implementation of an ion-select in order to demonstrate a voiceover issue, tested in iOs 16 and 17.

Issue:
Toggling between two selected options in the popup (md or ios mode) results in unintended voiceover output.

Steps to Recreate
1). With voiceover on, click to open the Test ion-select.
2). Select any option, like Yellow.
3). Select another option, like Red. Notice that voiceover outputs "Yellow, Red", instead of just "Red".
4). Select "Yellow" again. Voiceover outputs "Yellow, Red", instead of just "Yellow". 
