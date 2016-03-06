# nag
nag-matic calendar chain manager

Basic premise: There are events that have a necessary set of tasks (a chain) that must precede them.
nag provides the mechanism to automatically generate the tasks in the chain

Uses google calendar

Example:
  Event: research paper due on April 30th
  Chain events created:
     Perform Initial Research - April 16th
     First draft complete - April 18th
     First draft reviewed - April 20th
     Final candidate complete - April 27th
     Final candidate reviewed - April 29th
     Complete - April 29th
     Submitted - April 30th
     
  Allow difinitions of multi-chain templates
  nag will monitor how effective chains are
  
  nag will take into account weekend, weekdays, work hours, holiday, etc to alert early if there is risk to the chain
  
  Why nag?  Because it will nag you a lot using email, text, FB, etc the more you get off schedule
  
  
