# Package TEST_PMC\_PACK

***

| [clear\_count](broken-reference)                      | Procedure to clear massive of the cash documents                                              |
| ----------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [add\_object](broken-reference)                       | Procedure to add to the massive of the cash documents new cash document                       |
| [set\_trig\_on](broken-reference)                     | Procedure to on(logical) tiggers on the cash documents                                        |
| [set\_trig\_off](broken-reference)                    | Procedure to off(logical) tiggers on the cash documents                                       |
| [restore\_trig\_flag](broken-reference)               | Procedure to restore tiggers on the cash documents                                            |
| [trig\_raise](broken-reference)                       | Function to Get cash documents triggers state                                                 |
| [get\_prod\_info](broken-reference)                   | Function to get PMC product type Information                                                  |
| [get\_doc\_info](broken-reference)                    | Function to get Cash Document Information                                                     |
| [User\_Is\_Cashier](broken-reference)                 | Function to Check if the User is Cahsier                                                      |
| [Cashier\_Data\_By\_User](broken-reference)           | Function to Get Cashier parameters for by User                                                |
| [Cashier\_Id\_By\_User](broken-reference)             | Function to Get Cashier Primary key by User                                                   |
| [Dflt\_Run\_Date\_By\_User](broken-reference)         | Function to Get Cashier Run Date                                                              |
| [Amount\_In\_Cash](broken-reference)                  | Function to Get Cashier Amount in specified Currency                                          |
| [Cash\_Acct\_Key](broken-reference)                   | Function to Get Cashier Account primary key in the specified Currency                         |
| [Update\_Amount\_In\_Cash](broken-reference)          | Procedure to Change cashier amount in the specified currency                                  |
| [Input\_Complete](broken-reference)                   | Function to Set Default Accepts on the cash document                                          |
| [cash\_complete](broken-reference)                    | Function to Check if the banknote list is requered and filled for the Specified cash document |
| [Calc\_Doc\_Commission](broken-reference)             | Procedure to Calculate Default and Manual Cash Document Commissions                           |
| [banknote\_amt](broken-reference)                     | Function To Calculate amount for the Specified banknote Type, Currency, Amount                |
| [Recalc\_Commission](broken-reference)                | Function to Calculate Commission for PMC module                                               |
| [Calc\_Total\_Commission](broken-reference)           | Function to Calculate Total Commission Amount for Cash Document                               |
| [Prod\_Data](broken-reference)                        | Function to Get PMC Product type parameters                                                   |
| [Is\_Autoaccept\_Allowed](broken-reference)           | Function to Check if the Autoaccept Allowed                                                   |
| [Get\_Branch\_By\_bic](broken-reference)              | Function to Get Branch Code by BIC Code                                                       |
| [Get\_Self\_Cash\_Date](broken-reference)             | Function to Get Self Cash Date                                                                |
| [Check\_Available\_Amt](broken-reference)             | Procedure to Check, If the Amount is Available for the Account                                |
| [Is\_Autocash\_Allowed](broken-reference)             | Function to Check if the Autocash Allowed                                                     |
| [Check\_Sender\_Inn](broken-reference)                | Procedure to Check Sender INN                                                                 |
| [Check\_Sender\_Pin](broken-reference)                | Procedure to Check Sender PIN                                                                 |
| [Is\_Device\_Allowed](broken-reference)               |                                                                                               |
| [Set\_Default\_PMD\_Accepts](broken-reference)        |                                                                                               |
| [check\_acct\_for\_oper](broken-reference)            |                                                                                               |
| [Get\_Pmd\_Sample](broken-reference)                  |                                                                                               |
| [Calc\_Pmd\_Com](broken-reference)                    |                                                                                               |
| [Check\_Doc\_For\_Accept](broken-reference)           |                                                                                               |
| [Check\_Doc\_For\_Com\_Change](broken-reference)      |                                                                                               |
| [Get\_Acct\_Amt\_For\_Pmd](broken-reference)          |                                                                                               |
| [Check\_For\_Pmd](broken-reference)                   |                                                                                               |
| [Check\_Doc\_For\_Cli\_Acct\_Pmd](broken-reference)   |                                                                                               |
| [Get\_Pay\_Doc\_Oth\_Per\_Req](broken-reference)      |                                                                                               |
| [Check\_Client\_Params](broken-reference)             | Function to Check Client Age for Cash Operation Availability                                  |
| [Check\_For\_Card](broken-reference)                  |                                                                                               |
| [Commission\_Account\_Allowed](broken-reference)      |                                                                                               |
| [User\_Is\_Cashier\_Gizzeke](broken-reference)        |                                                                                               |

\


| [tab\_com\_object](broken-reference)      | type of the massive of the Cash document primary keys |
| ----------------------------------------- | ----------------------------------------------------- |
| [t\_System\_Info](broken-reference)       | PMC System information rowtype                        |
| [t\_PMC\_Doc\_Info](broken-reference)     | PMC Document information rowtype                      |
| [t\_PMC\_Prod\_Info](broken-reference)    | PMC Products parameters rowtype                       |
| [t\_PMC\_Doc\_Sample](broken-reference)   |                                                       |

\
\
\


***

tab\_com\_object

```
TYPE tab_com_object IS TABLE of pmc_cash_documents.doc_key%TYPE INDEX BY BINARY_INTEGER;
```

type of the massive of the Cash document primary keys

***

g\_obj\_no

```
g_obj_no  tab_com_object;
```

***

g\_obj\_ind

```
g_obj_ind BINARY_INTEGER;
```

***

gv\_raise\_trig

```
gv_raise_trig      boolean := true;
```

***

gv\_raise\_trig\_save

```
gv_raise_trig_save boolean;
```

***

t\_System\_Info

```
subtype t_System_Info is PMC_SYSTEM%rowtype;
```

PMC System information rowtype

***

t\_PMC\_Doc\_Info

```
subtype t_PMC_Doc_Info is PMC_CASH_DOCUMENTS%rowtype;
```

PMC Document information rowtype

***

t\_PMC\_Prod\_Info

```
subtype t_PMC_Prod_Info is PMC_PRODUCTS%rowtype;
```

PMC Products parameters rowtype

***

t\_PMC\_Doc\_Sample

```
subtype t_PMC_Doc_Sample is pmd_doc_samples%rowtype;
```

***

clear\_count

```
Procedure clear_count
```

Procedure to clear massive of the cash documents

***

add\_object

```
Procedure add_object(p_doc_key in pmc_cash_documents.doc_key%TYPE)
```

Procedure to add to the massive of the cash documents new cash document

|   | p\_doc\_key   | <p>cash document primary key<br></p> |
| - | ------------- | ------------------------------------ |

\


***

set\_trig\_on

```
Procedure set_trig_on
```

Procedure to on(logical) tiggers on the cash documents

***

set\_trig\_off

```
Procedure set_trig_off
```

Procedure to off(logical) tiggers on the cash documents

***

restore\_trig\_flag

```
Procedure restore_trig_flag
```

Procedure to restore tiggers on the cash documents

***

trig\_raise

```
Function trig_raise return boolean
```

Function to Get cash documents triggers state

|   | <p>true if the triggers on and return false if the triggers off<br></p> |
| - | ----------------------------------------------------------------------- |

\


***

get\_prod\_info

```
Function get_prod_info(p_prod_type varchar2) return t_pmc_prod_info
```

Function to get PMC product type Information

|   | p\_prod\_type   | <p>PMC product type<br></p> |
| - | --------------- | --------------------------- |

\


|   | <p><a href="broken-reference">t_pmc_prod_info</a> PMC Products parameters rowtype<br></p> |
| - | ----------------------------------------------------------------------------------------- |

\


***

get\_doc\_info

```
Function get_doc_info(p_internal_key number, p_obj_type varchar2)
  return t_pmc_doc_info
```

Function to get Cash Document Information

|   | p\_internal\_key   | <p>the Unique/Primary key of the object<br></p> |
| - | ------------------ | ----------------------------------------------- |
|   | p\_obj\_type       | <p>the type of the object<br></p>               |

\


|   | <p><a href="broken-reference">t_pmc_doc_info</a> PMC Document information rowtype<br></p> |
| - | ----------------------------------------------------------------------------------------- |

\


***

gc\_Chk\_Doc\_NO\_Errors

```
gc_Chk_Doc_NO_Errors        constant number(1) := 0;
```

***

gc\_Chk\_Doc\_SKP\_Not\_Complete

```
gc_Chk_Doc_SKP_Not_Complete constant number(2) := 10;
```

***

gc\_Chk\_Doc\_BNL\_Not\_Complete

```
gc_Chk_Doc_BNL_Not_Complete constant number(2) := 20;
```

***

gc\_Chk\_Doc\_APD\_Not\_Complete

```
gc_Chk_Doc_APD_Not_Complete constant number(2) := 40;
```

***

gc\_Chk\_Doc\_PMD\_Not\_Complete

```
gc_Chk_Doc_PMD_Not_Complete constant number(2) := 60;
```

***

User\_Is\_Cashier

```
Function User_Is_Cashier(P_user_name Varchar2 Default User) return boolean
```

Function to Check if the User is Cahsier

|   | p\_user\_name   | <p>the User name of the user, default User who execute this function<br></p> |
| - | --------------- | ---------------------------------------------------------------------------- |

\


|   | <p>True if the User is Cahsier and return False if the user is not Cashier<br></p> |
| - | ---------------------------------------------------------------------------------- |

\


***

Cashier\_Data\_By\_User

```
Function Cashier_Data_By_User(p_user_name Varchar2 Default User)
  return PMC_CASHIER_CODES%rowtype
```

Function to Get Cashier parameters for by User

|   | p\_user\_name   | <p>the User name of the user, default User who execute this function<br></p> |
| - | --------------- | ---------------------------------------------------------------------------- |

\


|   | <p>PMC Cashier parameters rowtype<br></p> |
| - | ----------------------------------------- |

\


***

Cashier\_Id\_By\_User

```
Function Cashier_Id_By_User(p_user_name Varchar2 Default User)
  return number
```

Function to Get Cashier Primary key by User

|   | p\_user\_name   | <p>the User name of the user, default User who execute this function<br></p> |
| - | --------------- | ---------------------------------------------------------------------------- |

\
\


***

Dflt\_Run\_Date\_By\_User

```
Function Dflt_Run_Date_By_User(p_user_name Varchar2 Default User)
  return date
```

Function to Get Cashier Run Date

|   | p\_user\_name   | <p>the User name of the user, default User who execute this function<br></p> |
| - | --------------- | ---------------------------------------------------------------------------- |

\
\


***

Amount\_In\_Cash

```
Function Amount_In_Cash(p_Cashier_Id in number, p_Cashier_Ccy in varchar2)
  return number
```

Function to Get Cashier Amount in specified Currency

|   | p\_Cashier\_Id    | <p>The casheir primary key<br></p> |
| - | ----------------- | ---------------------------------- |
|   | p\_Cashier\_Ccy   | <p>The Currency code<br></p>       |

\


|   | <p>Amount of the specified cashier in the specified currency<br></p> |
| - | -------------------------------------------------------------------- |

\


***

Cash\_Acct\_Key

```
Function Cash_Acct_Key(p_Cashier_Id in number, p_Cashier_Ccy in varchar2)
  return number
```

Function to Get Cashier Account primary key in the specified Currency

|   | p\_Cashier\_Id    | <p>The casheir primary key<br></p> |
| - | ----------------- | ---------------------------------- |
|   | p\_Cashier\_Ccy   | <p>The Currency code<br></p>       |

\
\


***

Update\_Amount\_In\_Cash

```
Procedure Update_Amount_In_Cash(p_Cashier_Id       in number,
                                p_Cashier_Ccy      in varchar2,
                                p_Amount_With_Sign in number)
```

Procedure to Change cashier amount in the specified currency\
@throws exception no\_data\_found if the specified cashier or specified cyrrency for cashier not found

|   | p\_Cashier\_Id          | <p>The casheir primary key<br></p>                |
| - | ----------------------- | ------------------------------------------------- |
|   | p\_Cashier\_Ccy         | <p>The Currency code<br></p>                      |
|   | p\_Amount\_With\_Sign   | <p>Amount which should be add or subtract<br></p> |

\


***

Input\_Complete

```
Function Input_Complete(p_Doc_Key in number, p_Error_Code out number)
  return boolean
```

Function to Set Default Accepts on the cash document\
@throws exception no\_data\_found if the specified Cash Document not found

|   | p\_Doc\_Key      | <p>The Cash Document Unique key<br></p> |
| - | ---------------- | --------------------------------------- |
|   | p\_Error\_Code   | <p>out Error Code<br></p>               |

\


|   | <p>True if the Accepts is Complete, False if not comlete<br></p> |
| - | ---------------------------------------------------------------- |

\


***

cash\_complete

```
Function cash_complete(p_doc_key in number, p_Error_Code out number)
  return boolean
```

Function to Check if the banknote list is requered and filled for the Specified cash document

|   | p\_Doc\_Key      | <p>The Cash Document Unique key<br></p> |
| - | ---------------- | --------------------------------------- |
|   | p\_Error\_Code   | <p>out Error Code<br></p>               |

\


|   | <p>True if the Banknote list is filled, False if not filled<br></p> |
| - | ------------------------------------------------------------------- |

\


***

Calc\_Doc\_Commission

```
Procedure Calc_Doc_Commission(p_Doc_Key     in number,
                              p_Recalc_Flag in varchar2 := 'N')
```

Procedure to Calculate Default and Manual Cash Document Commissions\
@throws exception no\_data\_found if the specified Cash Document not found\
@throws exception ORA-20222 If the account is linked to the plactic card and commisiion type not specified\
@throws exception ORA-20222 If the account is linked to the plactic card and found more then one linked commissions

|   | p\_Doc\_Key       | <p>The Cash Document Unique key<br></p>              |
| - | ----------------- | ---------------------------------------------------- |
|   | p\_Recalc\_Flag   | <p>default 'N' the sign of the recalculation<br></p> |

\


***

banknote\_amt

```
Function banknote_amt(p_ccy varchar2, p_bnknt_type varchar2, p_amt number)
  return number
```

Function To Calculate amount for the Specified banknote Type, Currency, Amount\
@throws exception no\_data\_found if the specified Cash Document not found\
@throws exception ORA-20222 If the account is linked to the plactic card and commisiion type not specified\
@throws exception ORA-20222 If the account is linked to the plactic card and found more then one linked commissions

|   | p\_ccy           | <p>The Curremcy code<br></p>               |
| - | ---------------- | ------------------------------------------ |
|   | p\_bnknt\_type   | <p>The type of the banknote<br></p>        |
|   | p\_amt           | <p>the Amount of the cash document<br></p> |

\
\


***

Recalc\_Commission

```
Function Recalc_Commission(p_Com_Type   in varchar2,
                           p_Doc_Amount in number,
                           p_Doc_Ccy    in varchar2,
                           p_Com_Ccy    in varchar2,
                           p_Branch     in varchar2,
                           p_Client_Key in number default null,
                           p_Acct_Key   in number,
                           p_Department in varchar2) return number
```

Function to Calculate Commission for PMC module

|   | p\_Com\_Type     | <p>The Commission type<br></p>                 |
| - | ---------------- | ---------------------------------------------- |
|   | p\_Doc\_Amount   | <p>The Document Amount<br></p>                 |
|   | p\_Doc\_Ccy      | <p>The Document Currency code<br></p>          |
|   | p\_Com\_Ccy      | <p>The Commission Currency code<br></p>        |
|   | p\_Branch        | <p>The Branch code<br></p>                     |
|   | p\_Client\_Key   | <p>default null The Client primary key<br></p> |
|   | p\_Acct\_Key     | <p>The Account primary key<br></p>             |
|   | p\_Department    | <p>The Department code<br></p>                 |

\


|   | <p>Calculated Commission Amount<br></p> |
| - | --------------------------------------- |

\


***

Calc\_Total\_Commission

```
Function Calc_Total_Commission(p_Doc_Key in number) return number
```

Function to Calculate Total Commission Amount for Cash Document

|   | p\_Doc\_Key   | <p>The Cash document Unique key<br></p> |
| - | ------------- | --------------------------------------- |

\


|   | <p>Calculated Total Commission Amount<br></p> |
| - | --------------------------------------------- |

\


***

Prod\_Data

```
Function Prod_Data(p_Prod_Type in varchar2) return PMC_PRODUCTS%rowtype
```

Function to Get PMC Product type parameters

|   | p\_Prod\_Type   | <p>The PMC Product type<br></p> |
| - | --------------- | ------------------------------- |

\
\


***

Is\_Autoaccept\_Allowed

```
Function Is_Autoaccept_Allowed(p_doc_key in Number) return varchar2
```

Function to Check if the Autoaccept Allowed

|   | p\_Doc\_Key   | <p>The Cash document Unique key<br></p> |
| - | ------------- | --------------------------------------- |

\
\


***

Get\_Branch\_By\_bic

```
Function Get_Branch_By_bic(p_bic in varchar2) return varchar2
```

Function to Get Branch Code by BIC Code

\
\


***

Get\_Self\_Cash\_Date

```
Function Get_Self_Cash_Date return date
```

Function to Get Self Cash Date

\


***

Check\_Available\_Amt

```
Procedure Check_Available_Amt(p_amount number, p_acct_key number)
```

Procedure to Check, If the Amount is Available for the Account\
@throws exception ORA-20222 If the account is not found by the specified primary key\
@throws exception ORA-20222 If the specified Amount is not available

|   | p\_Amount      | <p>The Document Amount<br></p>              |
| - | -------------- | ------------------------------------------- |
|   | p\_Acct\_Key   | <p>The Document Account primary key<br></p> |

\


***

Is\_Autocash\_Allowed

```
Function Is_Autocash_Allowed(p_doc_key in number) return varchar2
```

Function to Check if the Autocash Allowed

|   | p\_Doc\_Key   | <p>The Cash document Unique key<br></p> |
| - | ------------- | --------------------------------------- |

\
\


***

Check\_Sender\_Inn

```
Procedure Check_Sender_Inn(p_Inn varchar2)
```

Procedure to Check Sender INN\
@throws exception ORA-20222 If the Lehgth of the specified INN is not Correct\
@throws exception ORA-20222 If the Format of the specified INN is not Correct\
@throws exception ORA-20222 If the specified INN is not Correct\
@throws exception ORA-20222 If the specified INN is not start from 1 or 2

\


***

Check\_Sender\_Pin

```
Procedure Check_Sender_Pin(p_Pin varchar2)
```

Procedure to Check Sender PIN\
@throws exception ORA-20222 If the Lehgth of the specified PIN is not Correct\
@throws exception ORA-20222 If the Format of the specified PIN is not Correct

\


***

Is\_Device\_Allowed

```
Function Is_Device_Allowed(p_Doc_Key In Number) Return Varchar2
```

***

Set\_Default\_PMD\_Accepts

```
Procedure Set_Default_PMD_Accepts(p_Msg_Key       in number,
                                  p_Prod_Type     varchar2,
                                  p_Transfer_No   varchar2,
                                  p_Inp_Exec_Code varchar2)
```

***

check\_acct\_for\_oper

```
Function check_acct_for_oper(p_acct_key in number) return varchar2
```

***

Get\_Pmd\_Sample

```
Function Get_Pmd_Sample(p_Pay_Type in varchar2) return t_PMC_Doc_Sample
```

***

Calc\_Pmd\_Com

```
Function Calc_Pmd_Com(p_acct_key      in number,
                      p_amount        in number,
                      p_Pay_Type      in varchar2,
                      p_Dispatch_Type in varchar2 default null)
  return varchar2
```

***

Check\_Doc\_For\_Accept

```
Function Check_Doc_For_Accept(p_Doc_Key   in number,
                              p_Note_Text out varchar2) return varchar2
```

***

Check\_Doc\_For\_Com\_Change

```
Function Check_Doc_For_Com_Change(p_Doc_Key in number) return varchar2
```

***

Get\_Acct\_Amt\_For\_Pmd

```
Function Get_Acct_Amt_For_Pmd(p_Acct_Key number, p_Prod_Type varchar2)
  return number
```

***

Check\_For\_Pmd

```
Function Check_For_Pmd(p_Doc_key number, p_Prod_Type varchar2)
  return varchar2
```

***

Check\_Doc\_For\_Cli\_Acct\_Pmd

```
Function Check_Doc_For_Cli_Acct_Pmd(p_Doc_Key in number) return varchar2
```

***

Get\_Pay\_Doc\_Oth\_Per\_Req

```
Function Get_Pay_Doc_Oth_Per_Req(p_Pmc_Prod_type varchar2,
                                 p_Pay_Amt       number,
                                 p_Pmc_Amt       number) return varchar2
```

***

Check\_Client\_Params

```
Function Check_Client_Params(p_Acct_Key in number) return varchar2
```

Function to Check Client Age for Cash Operation Availability

|   | p\_Acct\_Key   | <p>Client Account Unique Key<br></p> |
| - | -------------- | ------------------------------------ |

\


|   | <p>'Y' if Available, 'N' Otherwise<br></p> |
| - | ------------------------------------------ |

\


***

Check\_For\_Card

```
Function Check_For_Card(p_Prod_Type varchar2) return varchar2
```

***

Commission\_Account\_Allowed

```
Function Commission_Account_Allowed(p_Acct_Key in number) return varchar2
```

***

User\_Is\_Cashier\_Gizzeke

```
Function User_Is_Cashier_Gizzeke(P_user_name Varchar2 Default User)
  return boolean
```
