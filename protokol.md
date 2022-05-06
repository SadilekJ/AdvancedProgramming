# AdvancedProgramming
Projekt do předmětu Pokročilé programování 2021/2022

## Scénář

HR jisté společnosti přijde za vývojáři s požadavkem na zpracování hodnocení pracovníků od kolegů pro zajištění podkladů na připravované hodnocení výkonu pracovníka za jeden rok od posledního hodnocení. Jednoduché formuláře spolu s emailovými notifikacemi o sbírání hodnocení a data ukončení spolu s připomínkami o vyplnění.

## Požadavky
1. Vytváření hodnocení na pracovníky od kolegů
2. Ukládání hodnocení do databáze
3. Nastavení hodnotitelů
4. Emailové notifikace pro všechny zúčastněné
5. Vytváření záznamu ze setkání s vedoucím pracovníkem

## Využité technologie
- .NET framework
- C# language
- SQL Database
- Linq
- Blazor
- RabbitMQ
- Background jobs
- Advanced debugging
- Email services
- Fluxor

## Časový plán
- Design stránky pro záznam hodnocení pracovníka s vedoucím - 7 hodin
- Přepsání frontend stránek do Fluxoru - 6 hodin
- Napojení backendu na frontend - 4 hodiny
- Tvorba databázových objektů - 3 hodiny
- Tvorba migrací a update databáze - 3 hodiny
- Přidání role administrátora - 4 hodiny
- Přidání role manažera - 4 hodiny
- Testování implementace - 6 hodin
- Přidat notifikace pro pracovníky, HR a vedoucí - 4 hodiny
- Přidání auditu vytvořených tabulek - 5 hodin
- Odebrání závislosti na externí službě - 5 hodin
