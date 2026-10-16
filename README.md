# SOC Detection Lab

## Цель
Собрать логи Windows через Sysmon, загрузить их в SIEM, 
сгенерировать атаку и провести расследование инцидента.

## Стек
- Windows 10 (VirtualBox)
- Sysmon (конфиг SwiftOnSecurity)
- Wazuh / Splunk Free
- MITRE ATT&CK для маппинга техник

## Что внутри
- `lab-setup/` — как развёрнута лаборатория
- `attacks/` — сценарии атак
- `detections/` — разбор событий и индикаторов
- `reports/` — итоговые инцидент-репорты
