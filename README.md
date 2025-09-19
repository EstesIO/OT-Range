# OT-Range: Industrial Control Systems Virtual Lab

**Author:** Grayson Estes

🏭 Deploy a complete OT/ICS testing environment in under 15 minutes on standalone ESXi.

---

## 🚀 Features

- **5 Prebuilt VMs**
  - Debian (HMI)
  - Ubuntu (Historian)
  - Windows 10 (Engineering)
  - Windows 7 (Legacy)
  - Rocky 8 (Gateway)

- **Industrial Protocols**
  - Modbus TCP/RTU
  - DNP3
  - EtherNet/IP
  - OPC UA

- **SCADA Systems**
  - OpenPLC
  - FUXA HMI
  - ScadaBR

- **Security Tools**
  - Network monitoring
  - Vulnerability scanners

- **Zero Configuration**
  - One-command deployment using `ot-range-repo.sh`

---

## 📂 Repo Structure

- `scripts/` → Deployment and helper scripts  
- `templates/` → VM templates / OVA files  
- `configs/` → Config files (YAML/JSON)  
- `docs/` → Documentation, architecture diagrams  
- `tools/` → Utilities  

---

## 🛠️ Usage

Clone this repo:

```bash
git clone https://github.com/EstesIO/OT-Range.git
cd ot-range/scripts
chmod +x ot-range-repo.sh
./ot-range-repo.sh
```

This will generate the **OT-Range repo structure** locally with placeholders for configs, docs, and tools.

---

## 🗺️ Roadmap

- [ ] Add VM OVA images or Packer templates
- [ ] Provide sample configs for Modbus, DNP3, OPC UA
- [ ] Expand docs with network diagrams
- [ ] Add CI/CD pipeline for automated lab build

---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.
