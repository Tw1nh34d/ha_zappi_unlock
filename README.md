# ha_zappi_unlock

Unlock Zappi after EV has been connected.

Requires curl command!

File: configuration.yaml
  shell_command:
      myenergi_curl_get: 'curl --digest -u {{ url }}'
