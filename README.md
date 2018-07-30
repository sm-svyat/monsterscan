# monsterscan
Looking for a job description on the website monster.com.

Installation

$ pip install --user mscan

Example

from mscan.mscan import MonsterScan
ms = MonsterScan('python')  
ms.search()  
ms.get_urls()  
ms.parce_urls()  
ms.save_vacancies('python.csv')
