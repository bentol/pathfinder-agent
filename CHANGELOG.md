## Changelog

#### 0.6.2
- Add the ability to capture additional metrics: loadavg & disks (root & ZFS)

#### 0.6.1
- Add bootstrap flag options as environment variables

#### 0.6.0
- Make bootstrap process idempotent
- Functionality to retry bootstrap if it failed
- Make number of concurrent bootstrap adjustable

#### 0.5.3
- Fix: Empty bootstrap template content

#### 0.5.2
- Avoid creating temporary file before writing bootstrap script on the container

#### 0.5.1
- Update endpoint address

#### 0.5.0
- Support bootstrapping container

#### 0.4.0
- Retry connecting to pathfinder mono when server is down
- Migrate to go modules
- Use pathfinder mono v2 API

#### 0.3.2
- Fix: Node ipaddress that is sent to mono

#### 0.3.1
- Fix: Default path for storing metrics

#### 0.3.0
- Add feature to collect metrics from node and store it on server

#### 0.2.0
- Model and pfclient are extracted to [pathfinder-go-client](https://github.com/pathfinder-cm/pathfinder-go-client) repo

#### 0.1.0
- Initial release: base agent functionality up and running.
