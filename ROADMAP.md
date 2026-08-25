# Hubuntu Public Roadmap

Roadmap ini menerangkan arah pembangunan Hubuntu pada tahap umum. Implementation dalaman dan eksperimen kekal dalam repository pembangunan private.

## 1. Experience

- Hubuntu Menu Core
- Hubuntu Folder Drawer
- Search dan kategori aplikasi
- Login Wallpaper Changer
- Window Animation Engine
- Icon animation
- UI desktop yang konsisten dan ringan

## 2. Performance

- Fast Boot
- Audit critical path systemd
- Fast Desktop Loading
- Lazy-load komponen tidak kritikal
- First Boot Optimizer
- Preset Balanced / Performance / Battery / Low Resource
- Hubuntu Performance Center

## 3. Update System

- Ubuntu kekal sebagai upstream base system
- Hubuntu Update Layer untuk komponen Hubuntu
- Stable / Testing / Developer channels
- Compatibility check sebelum update besar
- Safe Update Mode
- Snapshot dan rollback

## 4. Hubuntu Sentinel

Hubuntu Sentinel ialah konsep keselamatan berorientasikan network dan behaviour, bukan bergantung sepenuhnya kepada signature malware database.

Sasaran umum:

- Smart Firewall
- DNS Guard
- Process Network Profiling
- Connection anomaly detection
- Package Trust Guard
- Lightweight File & Process Guard
- Network Kill Switch
- Security Center
- Light / Balanced / Strict protection modes

## 5. Recovery

- Hubuntu Panic Lock
- Unfreeze desktop/session
- Standard State Repair dengan fail pengguna dikekalkan
- Factory Standard State
- Hubuntu Standard Restore Data
- Selective Restore
- Snapshot / Previous Working State

## 6. Hardware Intelligence

- CPU/GPU/RAM/storage detection
- Laptop/desktop detection
- Driver health
- Storage health
- Power/battery profile
- Hardware-aware optimization

## Development principle

Perubahan berisiko tinggi seperti boot, kernel, recovery dan security internals perlu diuji secara berasingan sebelum dipromosikan sebagai stabil. Sasaran hanya dianggap selesai selepas implementation telah diuji, bukan sekadar selepas kod ditulis.
