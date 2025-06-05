These config files should be stored in the Home Assistant `/config` folder.

They can be imported into the `configuration.yaml` file as such:
```yaml
media_player: !include mediaplayer.yaml
notify: !include notify.yaml
rest_command: !include rest_commands.yaml
template: !include template.yaml
rest: !include rest.yaml
```
