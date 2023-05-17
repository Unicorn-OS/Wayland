is_Wayland(){
  #from: https://bbs.archlinux.org/viewtopic.php?id=242733
  
  loginctl show-session $XDG_SESSION_ID | grep Type
}
