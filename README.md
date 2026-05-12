# chargeLedger Releases

Dieses Repository enthält öffentliche Release-Pakete für chargeLedger.

## Schnellstart

Stable installieren oder aktualisieren:

```bash
curl -fsSL https://raw.githubusercontent.com/ehive-dev/chargeLedger_releases/main/install.sh | sudo bash
```

Pre-Release installieren:

```bash
curl -fsSL https://raw.githubusercontent.com/ehive-dev/chargeLedger_releases/main/install.sh | sudo bash -s -- --pre
```

Bestimmte Version installieren:

```bash
curl -fsSL https://raw.githubusercontent.com/ehive-dev/chargeLedger_releases/main/install.sh | sudo bash -s -- --tag v0.2.3
```

## Service

```bash
systemctl status chargeledger --no-pager
journalctl -u chargeledger -f
```

Health-Check lokal:

```bash
curl http://127.0.0.1:3020/healthz
```

## Lizenz

Die Nutzung ist für private und nicht-kommerzielle Zwecke erlaubt. Kommerzielle Nutzung benötigt eine vorherige schriftliche Zustimmung von ehive. Siehe `LICENSE.txt` und `THIRD_PARTY_NOTICES.txt`.
