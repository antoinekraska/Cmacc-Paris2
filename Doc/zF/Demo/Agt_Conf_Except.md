Note0=This document is commented.  We build it up idea by idea, starting from the top.  (Ordinarily, we think of documents as being built from the bottom up. But it is easier to read a narrative from top to bottom.  So here we build from the top.)  When you click on "Document" you see the result.  To experiment, click on "Edit" and remove the "/" before a stage, then "Save" at the bottom, then click on "Document."  Feel free to mess with this: the original is at Github (link above) and your changes get discarded each time I update the Github repo or the site goes quiet for a while.

Note1=First an outline of a contract agreement.  This has a super-basic outline of an agreement.  "Deal, Relate, General".   

=[zF/Agt/00/Outline/Base/0.md]

Note2=Since we are making an NDA- we redirect the Deal to Conf.  

Deal.LI={Conf.LI}

Note3=We include a basic outline of confidentiality provisions.
  
/Conf.=[zF/Agt/00/Outline/Conf/0.md]

Note4=We focus on the exceptions to confidentiality, the Except part of Conf.  We select a set of Confidentiatiality provisions from a CooleyGo model.  

Conf.Except.=[Wx/com/cooleygo/US/NDA/Sec/Conf/Except/0.md]

Note5=But that CooleyGo document has the "Except" section on compliance with court order and other government compulsion in a separate section. 

/Conf.Except.Compelled.=[Wx/com/cooleygo/US/NDA/Sec/Conf/Except/Compelled/0.md] 

Note6=We want all the exceptions in a single section.  So we restate the Except section as having two subsections.   

Conf.Except.Sec=<b>{Conf.Except.Ti}</b><ol><li>{Conf.Except.sec}</li><li>{Conf.Except.Compelled.sec}</li></ol>

Note7=There are lots of defined terms in the text, so we include the CooleyGo list of defined terms.  

/_=[Wx/com/cooleygo/US/NDA/Sec/DefinedTerm/0.md]

Note8=This gives us a partial text that we can extend into a complete text, and use with a Frame to make a full Agreement with parties and signatures.