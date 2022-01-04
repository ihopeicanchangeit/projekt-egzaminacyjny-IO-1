# Projekt egzaminacyjny IO
## Cel projektu
### Opracowanie wymagań wstępnych oraz zarys kosztorysu zautomatyzowananej aplikacji tworzącej wirtualne laboratoria
Obecny system składa się z gotowych obrazów wirtualnych maszyn,zarówno studenckich jak i instruktorskich. Maszyny mają zainstalowany oprogramowanie Veyon do zdalnego zarządznia systemami maszyn wirtualnych. Na osobnym VPS-ie postawiony jest serwer VPN do którego podłączają się poszczególne maszyny laboratoryjne tworząc odosobnione środowisko laboratoryjne
### Aplikacja ma spełnić następujące wymagania:
1. Tworzyć grupy studenckie w osobnych podsieciach 
2. Umożliwiać dodawanie użytkownika do poszczególnych grup razem z listą ACL
3. Na maszynie wirtualnej instruktorskiej podczas łączenie klientem VPN ściąganie adresacji sieci którą ma przypisaną dany instruktor i wczytanie odpoowiedniej konfiguracji ustawień veyona
4. Wysyłanie kodów aktywacyjnych do poszczególnych studentów
5. 
