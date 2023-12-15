Use https://github.com/bullmoose20/Plex-Stuff#create_poster to create poster automatically.

With border :
`.\create_poster.ps1 -logo "C:\Users\margotp\Downloads\posters-by-bullmoose\transparent.png" -logo_offset +0 -logo_resize "" -text "THIS IS A TEST" -text_offset +0 -font "Comfortaa-Regular" -font_size 250 -font_color "#FFFFFF" -border 1 -border_width 50 -border_color "#FFFFFF" -avg_color_image "" -out_name "" -base_color "#CB7804" -gradient 1 -clean 0 -avg_color 0 -white_wash 0`

Without border :
`.\create_poster.ps1 -logo "C:\Users\margotp\Downloads\posters-by-bullmoose\transparent.png" -logo_offset +0 -logo_resize "" -text "THIS IS A TEST" -text_offset +0 -font "Comfortaa-Regular" -font_size 250 -font_color "#FFFFFF" -border 0 -border_width 50 -border_color "#FFFFFF" -avg_color_image "" -out_name "" -base_color "#CB7804" -gradient 1 -clean 0 -avg_color 0 -white_wash 0`
