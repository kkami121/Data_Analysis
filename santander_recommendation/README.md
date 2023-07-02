https://www.kaggle.com/competitions/santander-product-recommendation/data



## 산타데르 제품 추천
 - Santander 은행으로부터 1.5년간의 고객 행동 데이터를 제공받아 고객이 어떤 신제품을 구매할지 예측한다.
 - 데이터는 2015-01-28부터 시작되며 "신용 카드", "저축 계좌" 등과 같은 고객이 보유한 제품에 대한 월간 기록이 있다. 
 - 고객이 마지막 달인 2016-에 어떤 추가 제품을 받게 될지 예측할 수 있다.



 ### 데이터 설명
- fecha_dato - The table is partitioned for this column
- ncodpers - Customer code
- ind_empleado - Employee index: A active, B ex employed, F filial, N not employee, P pasive
- pais_residencia - Customer's Country residence
- sexo - Customer's sex
- age - Age
- fecha_alta - The date in which the customer became as the first holder of a contract in the bank
- ind_nuevo - New customer Index. 1 if the customer registered in the last 6 months.
- antiguedad - Customer seniority (in months)
- indrel - 1 (First/Primary), 99 (Primary customer during the month but not at the end of the month)
- ult_fec_cli_1t - Last date as primary customer (if he isn't at the end of the month)
- indrel_1mes - Customer type at the beginning of the month ,1 (First/Primary customer), 2 (co-owner ),P (Potential),3 (former primary), 4(former co-owner)
- tiprel_1mes - Customer relation type at the beginning of the month, A (active), I (inactive), P (former customer),R (Potential)
- indresi - Residence index (S (Yes) or N (No) if the residence country is the same than the bank country)
- indext - Foreigner index (S (Yes) or N (No) if the customer's birth country is different than the bank country)
- conyuemp - Spouse index. 1 if the customer is spouse of an employee
- canal_entrada - channel used by the customer to join
- indfall - Deceased index. N/S
- tipodom - Addres type. 1, primary address
- cod_prov - Province code (customer's address)
- nomprov - Province name
- ind_actividad_cliente - Activity index (1, active customer; 0, inactive customer)
- renta - Gross income of the household
- segmento - segmentation: 01 - VIP, 02 - Individuals 03 - college graduated
- ind_ahor_fin_ult1 - Saving Account
- ind_aval_fin_ult1 - Guarantees
- ind_cco_fin_ult1 - Current Accounts
- ind_cder_fin_ult1 - Derivada Account
- ind_cno_fin_ult1 - Payroll Account
- ind_ctju_fin_ult1 - Junior Account
- ind_ctma_fin_ult1 - Más particular Account
- ind_ctop_fin_ult1 - particular Account
- ind_ctpp_fin_ult1 - particular Plus Account
- ind_deco_fin_ult1 - Short-term deposits
- ind_deme_fin_ult1 - Medium-term deposits
- ind_dela_fin_ult1 - Long-term deposits
- ind_ecue_fin_ult1 - e-account
- ind_fond_fin_ult1 - Funds
- ind_hip_fin_ult1 - Mortgage
- ind_plan_fin_ult1 - Pensions
- ind_pres_fin_ult1 - Loans
- ind_reca_fin_ult1 - Taxes
- ind_tjcr_fin_ult1 - Credit Card
- ind_valo_fin_ult1 - Securities
- ind_viv_fin_ult1 - Home Account
- ind_nomina_ult1 - Payroll
- ind_nom_pens_ult1 - Pensions
- ind_recibo_ult1 - Direct Debit