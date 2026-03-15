# qsp

`qsp` is the meta-package for the RQM Technologies Quaternionic Signal Processing ecosystem.

Install everything with:

```bash
pip install qsp
```

This installs:

- qsp-core
- qsp-fft
- qsp-filter
- qsp-modulation
- qsp-orientation

## Example

```python
from qsp.fft import magnitude_spectrum
from qsp.filter import smoothing
from qsp.modulation import iq
from qsp.orientation import attitude
```