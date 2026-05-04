# ✈️ Smart Airport Network Demo & Infrastructure Design

This project provides a comprehensive network infrastructure design for a modern airport, accompanied by an interactive web-based UI demonstration. The core network was simulated using Cisco Packet Tracer 8.x[cite: 3], and it was developed as the Final Project for the BLM2006 – Introduction to Computer Networks course[cite: 3]. 

The repository includes both the frontend simulation dashboard (HTML/CSS/JS) and the documentation for the backend Cisco routing and switching architecture.

## 🚀 Key Features

*   **VLAN Segmentation:** Logically separated networks for arrival/departure passengers (VLAN 20, 21), administrative offices (VLAN 99), and the data center (VLAN 50)[cite: 3].
*   **Cisco ASA Firewall & NAT:** Implementation of boundary security between the internal network and the Internet using dynamic NAT and ACL policies[cite: 3].
*   **EtherChannel:** Bandwidth aggregation and link redundancy established between the Core Switch and Access Switches[cite: 3].
*   **Wireless LAN Controller (WLC):** Centralized management of Access Points via CAPWAP tunnels[cite: 3].
*   **Port Security:** Prevention of unauthorized device access utilizing sticky MAC addressing; violating ports automatically transition to err-disable mode[cite: 3].
*   **DHCP & DNS Services:** Automated IP distribution via the Core Switch and centralized name resolution for all VLANs[cite: 3].

## 🛠️ Tools & Technologies
*   **Network Simulation:** Cisco Packet Tracer 8.x[cite: 3]
*   **Frontend Demo:** HTML5, CSS3, JavaScript (Vanilla)

## 👥 Project Team (Group 3)
*   İdil Şen[cite: 3]
*   Metehan Aydoğdu[cite: 3]
*   Tunahan Kavaklı[cite: 3]



# ✈️ Akıllı Havalimanı Ağ Altyapı Tasarımı ve Demo Platformu

Bu proje, modern bir havalimanının karmaşık gereksinimlerini karşılamak üzere tasarlanmış kapsamlı bir ağ altyapısı sunmaktadır[cite: 3]. BLM2006 – Bilgisayar Ağlarına Giriş dersi final projesi kapsamında Cisco Packet Tracer 8.x kullanılarak geliştirilmiştir[cite: 3]. 

Bu depo (repository), hem hazırlanan ağ altyapısının dökümantasyonunu hem de sistemin yolcu ve IT personeli tarafında nasıl çalıştığını gösteren interaktif bir web arayüzü demosunu içermektedir.

## 🚀 Temel Özellikler

*   **VLAN Segmentasyonu:** Gelen/giden yolcular (VLAN 20, 21), idari personel (VLAN 99) ve yetkili sunucular (VLAN 50) için mantıksal ağ ayrımı yapılmıştır[cite: 3].
*   **Cisco ASA Firewall ve NAT:** İç ağ ile İnternet arasındaki sınır güvenliği, dinamik NAT ve ACL politikaları ile Cisco ASA 5505 üzerinden sağlanmıştır[cite: 3].
*   **EtherChannel:** Core Switch ile Access Switch'ler arasında bağlantı yedekliliği ve bant genişliği artırımı uygulanmıştır[cite: 3].
*   **WLC Entegrasyonu:** Havalimanı içindeki Access Point'lerin CAPWAP üzerinden merkezi yönetimi gerçekleştirilmiştir[cite: 3].
*   **Port Security:** Switch portlarında yetkisiz MAC adresleri engellenmiş, ihlal durumunda portların kapatılması (shutdown) sağlanmıştır[cite: 3].
*   **DHCP ve DNS Servisleri:** Core switch üzerinden otomatik IP ataması yapılmış ve merkezi DNS sunucusu kurulmuştur[cite: 3].

## 🛠️ Kullanılan Araçlar
*   **Ağ Simülasyonu:** Cisco Packet Tracer 8.x[cite: 3]
*   **Arayüz (Demo):** HTML5, CSS3, JavaScript 

## 👥 Proje Ekibi (Grup 3)
*   İdil Şen[cite: 3]
*   Metehan Aydoğdu[cite: 3]
*   Tunahan Kavaklı[cite: 3]


