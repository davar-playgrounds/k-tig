# K-TIG Kafka, Telegraf, InfluxDB and Grafana playground

Work in progress

Analytics & Monitoring software bundled up into convenient docker containers.

1. Kafka + zookeeper
1. Telgraf
1. InfluxDB
1. Grafana
1. Chronograf

Web UI details:

1. http://localhost:8087/ - Chronograf Web UI.
1. http://localhost:3000/ - Grafana Web UI.

## How to

1. Clone the repo.

    ```shell
    $ git clone https://github.com/zvfvrv/k-tig.git
    ```
1. Move to the cloned directory
    ```shell
    $ cd k-tig
    ```

1. Deploy the Docker stack
    ```shell
    $ docker stack deploy -c docker-compose.yml <stack_name>
    ```

If you need to remove the docker stack

```shell
$ docker stack rm <stack_name>
```
