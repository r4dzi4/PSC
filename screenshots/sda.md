### Integracja z Windows Server i Usługi Systemowe

* **Usługi Infrastrukturalne:** W VLAN 30 postawiłem działający **Windows Server**, który dostarcza kluczowe usługi **DHCP** i **DNS** dla maszyn w innych segmentach sieci.
* **Usługi Domenowe (Active Directory AD DS):** Wdrożono domenę korporacyjną oraz logiczną strukturę jednostek organizacyjnych (**OU**) odzwierciedlającą podział na działy firmy, wraz z zarządzaniem kontami użytkowników i komputerów.
  
  *(Przykład struktury działów w Active Directory)*
  ![Struktura AD](screenshots/Drzewo_GPO.png)

* **Scentralizowane Zarządzanie i Bezpieczeństwo (GPO):** Skonfigurowano zasady grupy (**Group Policy Objects**) dla stacji roboczych z systemem Windows 10, w tym zaawansowane zasady audytu systemu (**Advanced Audit Policy**) monitorujące zdarzenia logowania i bezpieczeństwa.

  *(Konfiguracja zaawansowanego audytu)*
  ![Advanced Audit Policy](screenshots/GPO.png)
