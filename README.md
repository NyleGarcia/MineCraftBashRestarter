# MineCraftBashRestarter
Minecraft server restarter for bash
requires tmux and 'at'

guides for at and tmux
https://gist.github.com/MohamedAlaa/2961058
http://www.computerhope.com/unix/uat.htm


sh ./restarter <session name> h m s (broadcast/say) "optinal message"

examples 

sh ./restarter hermitpack >> begins coutdown to restart hermitpack in 5 min

sh ./restarter hermitpack 0 20 0 >> begins coutdown to restart hermitpack in 20 min

sh ./restarter hermitpack 0 5 0 say Potato>> begins coutdown to restart hermitpack in 5 min using say instead of broadcast and says potato with each warning



