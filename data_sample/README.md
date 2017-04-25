# Data Sample

---
- discharge summaries and progress notes of 9 patients (combined together for each patient)
- .xml file is the text within CEMR
- .rf file is the risk factor annotation

---
##### Details of the risk factors in "patient1.xml.rf"
- C: risk factor content
- P: position in the text
- T: risk factor type
- I: indicator
- TA: time attribute
- A: assertion


C=老年 P=620:622 T=age I=age_group

C=男 P=622:623 T=gender I=mention

C=糖尿病病史五年 P=628:635 T=diabetes I=mention TA=continue A=present

C=长期吸烟史 P=655:660 T=smoke I=mention TA=continue A=present

C=每日约20支 P=662:668 T=smoke I=smoking_amount TA=continue A=present

C=Bp135/60mmHg P=842:854 T=hypertension I=high_bp TA=during A=present

C=老年 P=1075:1077 T=age I=age_group

C=男 P=1077:1078 T=gender I=mention

C=糖尿病病史五年 P=1108:1115 T=diabetes I=mention TA=continue A=present

C=长期吸烟史 P=1135:1140 T=smoke I=mention TA=continue A=present

C=每日约20支 P=1142:1148 T=smoke I=smoking_amount TA=continue A=present

C=Bp135/60咖Hg P=1174:1185 T=hypertension I=high_bp TA=during A=present
