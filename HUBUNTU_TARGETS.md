# Hubuntu Public Development Targets

Dokumen ini ialah tracker awam untuk menunjukkan hala tuju dan kemajuan Hubuntu. Source code dan implementation development sebenar tidak disimpan dalam repository public ini.

## Cara membaca status

- `[x]` Selesai dan telah diuji.
- `[ ]` Belum selesai / masih dalam pembangunan.

---

# 1. Experience

## Hubuntu Menu Core

- [x] Hubuntu Menu Core dipasang sebagai menu utama Hubuntu.
- [x] Menu Core menggunakan layout kategori.
- [x] Security tools diselaraskan ke Hubuntu Menu Core.
- [x] 8 kategori security dipaparkan sebagai submenu.
- [x] Susunan kategori security dikekalkan mengikut susunan asal.
- [ ] Audit dan kemaskan UI/UX Menu Core.
- [ ] Pastikan Menu Core kekal stabil selepas kemas kini GNOME/Ubuntu.

## Hubuntu Folder Drawer

- [ ] Floating application drawer di tengah desktop.
- [ ] Paparkan aplikasi sebenar menggunakan ikon sistem.
- [ ] Grid aplikasi responsif.
- [ ] Nama aplikasi di bawah ikon.
- [ ] Search aplikasi.
- [ ] Sokongan folder/kategori aplikasi.
- [ ] Scroll untuk senarai aplikasi panjang.
- [ ] Animasi buka/tutup yang ringan.
- [ ] Klik di luar drawer untuk tutup.
- [ ] Escape untuk tutup.
- [ ] Ikon grid / Show Applications membuka Hubuntu Folder Drawer.
- [ ] Fallback kepada GNOME App Grid jika drawer gagal.

## Login & Animation

- [ ] Login Wallpaper Changer.
- [ ] Preview dan reset wallpaper login.
- [ ] Window Animation Engine.
- [ ] Open/close/minimize/maximize animation.
- [ ] Icon animation.
- [ ] Pastikan animasi ringan dan GPU-friendly.

---

# 2. Performance

- [ ] Audit boot menggunakan systemd tools.
- [ ] Kenal pasti critical path boot.
- [ ] Kurangkan blocking semasa boot.
- [ ] Tangguhkan servis bukan kritikal secara selamat.
- [ ] Audit masa login hingga desktop usable.
- [ ] Lazy-load komponen Hubuntu yang tidak kritikal.
- [ ] Cache menu/icon/data yang sesuai.
- [ ] First Boot Optimizer.
- [ ] Balanced profile.
- [ ] Performance profile.
- [ ] Battery profile.
- [ ] Low Resource profile.
- [ ] Hubuntu Performance Center.

---

# 3. Update System

- [ ] Ubuntu kekal sebagai upstream rasmi untuk base system.
- [ ] Hubuntu repository untuk komponen khas Hubuntu.
- [ ] Bezakan Ubuntu System Update dan Hubuntu Experience Update.
- [ ] Stable channel.
- [ ] Testing channel.
- [ ] Developer channel.
- [ ] Compatibility check sebelum update besar.
- [ ] Post-update health check.
- [ ] Snapshot sebelum update besar.
- [ ] Safe Update Mode.
- [ ] Automatic rollback jika health check gagal.

---

# 4. Hubuntu Sentinel

Matlamat umum: perlindungan network/behaviour oriented dengan overhead rendah dan tanpa bergantung sepenuhnya kepada malware signature database.

- [ ] Hubuntu Security Center.
- [ ] Smart Firewall.
- [ ] Home / Public / Trusted profiles.
- [ ] DNS Guard.
- [ ] Process Network Profiling.
- [ ] Application behaviour baseline.
- [ ] Connection anomaly detection.
- [ ] Trusted traffic fast path.
- [ ] Deep analysis hanya untuk event mencurigakan.
- [ ] Package Trust Guard.
- [ ] Lightweight File & Process Guard.
- [ ] Network Kill Switch.
- [ ] Light protection mode.
- [ ] Balanced protection mode.
- [ ] Strict protection mode.
- [ ] Sasaran idle CPU dan network overhead serendah mungkin.

---

# 5. Recovery

## Hubuntu Panic Lock

- [ ] Recovery tidak bergantung kepada GNOME Shell sahaja.
- [ ] Boleh dipanggil ketika desktop/session freeze jika sistem teras masih responsif.
- [ ] Unfreeze.
- [ ] Standard State Repair dengan fail pengguna dikekalkan.
- [ ] Factory Standard State.
- [ ] Recovery fallback path.

## Standard Restore Data

- [ ] Cipta baseline recovery selepas pemasangan standard disahkan stabil.
- [ ] Lindungi baseline daripada perubahan biasa.
- [ ] Integrity verification.
- [ ] Package/component manifest.
- [ ] Full System Restore.
- [ ] Kernel Restore.
- [ ] Boot Restore.
- [ ] System Core Restore.
- [ ] System Configuration Restore.
- [ ] Hubuntu Components Restore.
- [ ] Desktop Settings Restore.
- [ ] Service Restore.
- [ ] Driver Configuration Restore.
- [ ] Selective restore dengan compatibility check.
- [ ] Snapshot / Previous Working State.

---

# 6. Hardware Intelligence

- [ ] CPU/GPU/RAM/storage detection.
- [ ] Laptop/desktop detection.
- [ ] Driver health.
- [ ] Storage health.
- [ ] Power/battery profile.
- [ ] Hardware-aware optimization.

---

# Public Project Principle

1. Repository public ini digunakan untuk dokumentasi, roadmap, status dan release information.
2. Development implementation dan eksperimen kekal private.
3. Sasaran hanya ditanda `[x]` selepas benar-benar berfungsi dan telah diuji.
4. Perubahan berisiko seperti kernel, boot dan recovery diuji secara terasing sebelum dianggap stabil.
5. Ubuntu kekal sebagai base/upstream Hubuntu.
