# ha_zappi_unlock

Unlock Zappi after EV has been connected.

> [!TIP]
> Requires curl command!


## configuration.yaml
```yaml
  shell_command:
      myenergi_curl_get: 'curl --digest -u {{ url }}'
