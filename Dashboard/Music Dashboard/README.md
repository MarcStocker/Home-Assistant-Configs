Most cards on this page make use of a Helper Entity (input_select) and [custom:config-template-card](https://github.com/iantrich/config-template-card). 

The Helper Entity, `input_select.music_broadcast_select`, contains a list of media player entity_id's. 
The purpose of this list is to target possible media players to allow playback control, display "Now Playing" info on the dashboard, and send Spotify albums for playback. 

The `config-template-cards` help to allow the cards to update whenever the Helper Entity is updated with a new Media Player. 

The "Music" button on the [Main Dashboard](https://github.com/MarcStocker/Home-Assistant-Configs/tree/main/Dashboard/Main%20Dashboard) also makes use of the above. 
<p align="center">
  <img src="https://github.com/user-attachments/assets/f5dbc15b-addf-48ca-b36d-75d18195b8f5" alt="Image 1" width="35%" />
  <img src="https://github.com/user-attachments/assets/28529bea-d7a6-40a2-ae14-7ebe9b1d6553" alt="Image 2" width="55%" />
</p>
