# DatasetforrobustRIP

## Description

  The datasets include the randomly generated instances and computational results of the robust RIP derived from an aircraft final-assembly line. The users can gain more detailed information about the computational experiments by referring to the datasets.

## Platform and Environment

  No special requirements. The included files can be opened by Excel or Txt. 

## Major Component Description

### Instance set
  For each instance, its parameters consist of three parts: “jxxx_x_par.xlsx”, “jxxx_x_group.xlsx” and “jxxx_x.sm” or “jxxx_x.mm” (in the folder “precedence relations”). “jxxx_x” represents the serial number of an instance. For example, j1010_1, the first 10 means the instance has 10 non-dummy processes, the 10_1 means the number of this instance. 
  
  The “jxxx_x_par.xlsx” contains processing times, workers required by each process, completion time and number of test processes. The “jxxx_x_group.xlsx” contains the unit cost of each task group and the processes in each task group. The precedence relations of each instance can be found in “PRECEDENCE RELATIONS” of “jxxx_x.sm” or “jxxx_x.mm”. 
  
  The “jxxx_x.sm” or “jxxx_x.mm” are the instances randomly draw from PSPLIB, where only the precedence relations are used.

 ### Result set
  “CompleteCCG_x” contains the results obtained by the complete C&CG algorithm on the instances with x processes, where “TC” is total resource investment cost, “Gap” denotes the gap between LB and UB of the C&CG algorithm, “Time” means CPU time in seconds and “IT” means the iterations of the C&CG algorithm. Moreover, for 20 and 30 processes, the results corresponding to different budgets of uncertainty represented by \varepsilon are given. 
  
  “PureCCG”, “SelfstartCCG” and “Compact” are the results obtained by pure C&CG algorithm, the C&CG algorithm only with self-start technique and the compact reformulation adapted from literature, respectively. 
  
  “Completiontime_x” contains the results under different completion times obtained by solving the instances with x processes.
  
  “lamda_x” contains the results under different levels of uncertainty (represented by \lambda) by solving the instances with x processes. 
  
  Note that, for the “\jxxxx_x_x” in the “instance” column, the last “x” has no actual implications. 

## Contact Information

  If you have any questions, please contact me by E-mail: b18321889254@163.com.
