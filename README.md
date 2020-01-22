# ansible-role-yace
Role for deploying yet-another-cloudwatch-exporter

----

https://github.com/ivx/yet-another-cloudwatch-exporter


# Role variables

| Name              | Default value | Description               |
|-------------------|---------------|-------------              | 
| `yace_version`    | `0.14.7-alpha`| Version of YACE to install|
| `yace_config_dir` | `/etc/yace/`  | Config dir where to put YACE config files |
| `yace_config`     | ""            | Yace config according to this [example](https://github.com/ivx/yet-another-cloudwatch-exporter#example-of-config-file) |
