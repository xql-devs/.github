# xql-devs

We're building a **SQL layer on top of [Zarr](https://zarr.dev/)** — bringing
familiar, declarative SQL querying to multidimensional array data.

This organization hosts all the repositories related to that effort.

## What we're working on

Zarr is a great format for chunked, compressed N-dimensional arrays, but
querying it usually means writing imperative array code. Our goal is to let you
point SQL at Zarr stores and get back the data you want, with the array world
and the relational world meeting in the middle.

## Key tech stack

- **[Xarray](https://xarray.dev/)** — labeled, multidimensional array model and
  the bridge to Zarr.
- **[DataFusion](https://datafusion.apache.org/)** — query planning and
  execution engine.
- **[DuckDB](https://duckdb.org/)** — in-process analytical SQL engine.

## Repositories

Browse the repositories in this organization to see the individual components.
More details and contribution guidelines will land here as the project grows.
