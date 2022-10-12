# Payroll-Data-Analyzer
Payroll Data Analysis: Payroll data analytics is the process of using payroll data and applying data analytics to it that allows businesses to understand economic trends and patterns so they can make better decisions.
Payroll processing data is information that is generated from companies conduct on monthly or bi-weekly bases. Payroll processing refers to benefits and payroll administration, and can be used as a key source for important information to fuel strategic insights. Looking at payroll processing data reveals the frequency of payments leaving a company every pay period, and can show when hiring trends are increasing or decreasing. 
Payroll data analysis extends the capability of traditional payroll services by offering a different view into payroll information.
The analysis reveals the frequency of payments, number of payees, and the amounts paid, but does not identify employees on an individual level. With a holistic view of payroll deposit data, from payment to deposit, businesses can discover trends and patterns in the market so they can use them to make better decisions.

###
	Field	                      Datatype	Description	Notes
	Employee number	            str	Unique identifier for each employee	This is used to link to the employee master data table
	Payment date	              date	Date that the payroll payment was made	
	Payment method	            str	How the payroll payment was made	
	Net pay	                    int	Total net pay for this payroll payment	
	Gross pay	                  int	Total gross pay for this payroll payment	
	Basic pay	                  int	Individual element of gross pay - basic pay	
	Overtime	                  int	Individual element of gross pay - overtime	
	Holiday pay	                int	Individual element of gross pay - holiday pay	
	Bonuses	                    int	Individual element of gross pay - bonus payments	
	Other gross1	              int	Individual element of gross pay - any other gross pay element	
	Other gross2	              int	Individual element of gross pay - any other gross pay element	
	Other gross3	              int	Individual element of gross pay - any other gross pay element	
	Payroll tax       	        int	Tax (other than social security) deducted from gross pay	Deduction paid by the employee
	Employee social security	  int	Employee's social security contributions deducted from gross pay	Deduction paid by the employee
	Employee pension	          int	Employee's pension contributions deducted from gross pay	Deduction paid by the employee
	Other deductions	          int	Any other deductions from gross pay	Deduction paid by the employee
	Employer social security	  int	Employer's social security expense	Expense paid by the employer
	Employer pension	          int	Employer's pension expense	Expense paid by the employer
	Hours	                      int	Hours worked during the payroll period	
	User Defined PD1	          str	User defined field	
	User Defined PD2	          str	User defined field	
	User Defined PD3	          str	User defined field	
	User Defined PD4	          str	User defined field	
	User Defined PD5	          str	User defined field	


###
