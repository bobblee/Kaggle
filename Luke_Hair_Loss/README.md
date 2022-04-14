
Columns & Description : 
- date [PK]
    - Date the observation has been recorded
- hair_loss
    - There are 4 levels of hair loss status
- stayuplate
    - The hours that stayed up for
- libido
    - This was used to objectively measure hormone level
- hair_grease
- pressure_level
    - 4 levels of pressure that has been felt
- coffee_consumed
    - Numbers of the cups of coffe has been consumed within the day
- brain'work'duration
    - How many works which requires brian power has been done, measured by hours.
- school_assessment
    - Whether has been doing assessment and the assessment type.
- stress_level
    - Whether has been doing assessment and the assessment type.
- shampoo_brand
    - The shampoo brands
- swimming
    - This one was picked because I thought that a long time soaking in poor quality water could cause hair fall out
    - Whether swimmed in that day
- hair_washing
- dandruff

|variable                    |PK|class     |description |
|:---------------------------|--|:---------|:-----------|
|date                        |Y |DD-MM-YYYY| Date the observation has been recorded |
|hair_loss                   |N |          |  |
|stayuplate                  |N |          |  |
|libido                      |N |          |  |
|hair_grease                 |N |          |  |
|pressure_level              |N |          |  |
|coffee_consumed             |N |          |  |
|brain'work'duration         |N |          |  |
|school_assessment           |N |          |  |
|stress_level                |N |          |  |
|shampoo_brand               |N |          |  |
|swimming                    |N |          |  |
|hair_washing                |N |          |  |
|dandruff                    |n |          |  |

Appendix : 
- Create venv:
    - create venv : python -m venv venv
    - open venv in terminal : .\venv\Scripts\activate.bat
    - upgrade pip : pip install --upgrade pip
    - When Upgrading Python
        - python -m venv --upgrade
    - If pip doesn't work
        - python -m ensurepip
        - python -m pip install --upgrade pip
- Pip Install Packages:
    - Create Requirements.txt
    - Run "pip install -r requirements.txt"