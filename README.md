# Identity Attack Path 3D Galaxy

Show identity graph attack paths as a 3D galaxy map.

## Priority Metadata

- ID: 180
- Domain: spatial-3d
- TTE (days): 6
- Exposure score: 9/10
- Wave: 2
- Priority score: 7.00

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
