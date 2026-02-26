files for the SP26 PBHLTH142 Data Project

dataset adapted from NHANES 2021-2023, filtering inspired by STAT C131A

to download the dataset via datahub, run the following in the **terminal**. Make sure you are in the right working directory:

```wget https://raw.githubusercontent.com/kittyjosh111/pbhlth142-dataproject/refs/heads/main/nhanes.csv```

to download this entire repository via datahub, run this in the **terminal**:

```git clone https://github.com/kittyjosh111/pbhlth142-dataproject.git```

---

Dataset description:

```
> data_description
             variable                                        labels
1                  id                    NHANES partiipant ID (dbl)
2                 age                                     Age (dbl)
3                 sex                                     Sex (chr)
4                race                                    Race (chr)
5   income_to_poverty                  Income to Poverty Ratio (db)
6           education                      Education Category (chr)
7            marriage                Marriage Status Category (chr)
8      household_size           Number of People in Household (dbl)
9                 bmi                               BMI Value (dbl)
10           is_obese                Obese Binary [1 = Obese] (dbl)
11          fiber_den            Fiber Density in g/1000 kcal (dbl)
12          sugar_den            Sugar Density in g/1000 kcal (dbl)
13         satfat_den    Saturated Fat Density in g/1000 kcal (dbl)
14         sodium_den           Sodium Density in g/1000 kcal (dbl)
15               kcal                   Energy Intake in kcal (dbl)
16     protein_intake                     Protein Intake in g (dbl)
17        carb_intake                Carbohydrate Intake in g (dbl)
18       fiber_intake                       Fiber Intake in g (dbl)
19       sugar_intake                       Sugar Intake in g (dbl)
20         fat_intake                         Fat Intake in g (dbl)
21      sodium_intake                      Sodium Intake in g (dbl)
22  cant_afford_meals Couldn't Afford Balanced Meals Category (chr)
23      food_security            Adult Food Security Category (chr)
24   health_condition                General Health Condition (chr)
25    health_location                     Healthcare Location (chr)
26 seen_mental_health    Seen Mental Health Professional in past yr
```
