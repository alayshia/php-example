# Honeycomb PHP Example

The following example uses Zipkin-PHP to send information to Honeycomb

## Requirements

- Docker
- Tilt (optional.)

### Setting the ENV variables

Using Honeycomb Classic? `HONEYCOMB_API_KEY=XXXXX` and `HONEYCOMB_DATASET_NAME=name`

Using Honeycomb Environments and Services? `HONEYCOMB_API_KEY=XXXXX`

## Running the Example Using Tilt

```bash
tilt up
```

## Running the Example Using Docker

```bash
docker compose up
```

## Create the Request

`curl <http://localhost:8081>`
