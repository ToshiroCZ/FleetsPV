# FleetsPV
Popis projektu
Fleet Management System je webová aplikace pro správu flotily vozidel, zákazníků a rezervací. Umožňuje správu vozidel, přidávání zákazníků, tvorbu rezervací a generování reportů.

Technologie
Backend: Flask (Python)
Frontend: HTML, CSS, Bootstrap
Databáze: Microsoft SQL Server
Další knihovny:
Flask-Bcrypt (pro šifrování hesel)
Flask-Login (pro autentizaci a správu uživatelů)
SQLAlchemy (ORM)
Hlavní funkce
Autentizace uživatelů:
Registrace, přihlášení, odhlášení
Správa uživatelského profilu
Správa vozidel:
Přidávání, úprava a mazání vozidel
Rezervace:
Přidávání zákazníků a jejich rezervací
Propojení rezervací se zákazníky a vozidly
Reporty:
Souhrnné reporty o počtu rezervací, příjmech, vozidlech apod.
Práce s databází:
Podpora transakcí
Generování reportů pomocí uložených procedur

Start:
stáhnout projekt
cd fleet-management
py -m venv venv
venv\Scripts\activate
Upravte připojení v souboru config.json
pip install -r requirements.txt
python app.py
