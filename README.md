# ani-cli-extended
More android players to ani-cli.
Add these lines in the "play_episode()" function

## MpvKt
~~~
android_mpvkt) nohup am start --user 0 -a t.action.VIEW -d "$episode" -n live.mehiz.mpvkt/live.mehiz.mpvkt.ui.player.PlayerActivity -e "title" "${allanime_title}Episode ${ep_no}" >/dev/null 2>&1 & ;;
~~~

## MpvExtended
~~~
android_mpvex) nohup am start --user 0 -a .VIEW -d "$episode" -n app.marlboroadvance.mpvex/app.marlboroadvance.mpvex.ui.player.PlayerActivity -e "title" "${allanime_title}Episode ${ep_no}" >/dev/null 2>&1 & ;;
~~~
