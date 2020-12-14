CodersNote=A basic outline for an NDA.  Borrowing some terms from "TechContracts.com".

CodersNote=We start with the basic frame for an Agreement - header, parties, why, sections, signature.

=[G/NW-NDA/00/Form/Agt-Frame.md]

sec=<ol><li>{Prime.Sec}<li>{Def.Sec}<li>{General.Sec}<li>{Misc.Sec}</ol>

CodersNote=We borrow TechContracts' notion of "Prime" clauses - the business terms.

Prime.Sec=<b>{Prime.Ti}</b><br>{Intro.sec}<ol><li>{Use.Sec}</li><li>{IP.Sec}</li><li>{Convey.Sec}</li><li>{ConfInfo.Sec}</li></ol>

Use.Sec=<b>{Use.Ti}</b><br><ol><li>{Use.Purpose.Sec}</li><li>{Use.Analyze.Sec}</li></ol>

IP.Sec=<b>{IP.Ti}</b><br><ol><li>{IP.Had.Sec}</li><li>{IP.Make.Sec}</li></ol>

CodersNote="Convey" is for the intended movement of information.  Confide, Circulate, Copy, Return.  Disclosure to a non-party is an unintended risk, handled in the General terms.

CodersNote="Convey" is something like the notion of "Happy Path", what is supposed to happen with information confided by the Provider to the Recipient.  Most of the rest is background or risk management.

Convey.Sec=<b>{Convey.Ti}</b><br><ol><li>{Confide.Sec}</li><li>{Circulate.Sec}</li><li>{Copy.Sec}</li><li>{Return.Sec}</li></ol>

Confide.Sec=<b>{Confide.Ti}</b><br><ol><li>{Confide.Scope.Sec}</li><li>{Confide.Method.Sec}</li></ol>

Circulate.Sec=<b>{Circulate.Ti}</b><br><ol><li>{Circulate.ToWhom.Sec}</li><li>{Circulate.Conditions.Sec}</li></ol>

Copy.Sec=<b>{Copy.Ti}</b><br><ol><li>{Copy.Permitted.Sec}</li><li>{Copy.Tracking.Sec}</li></ol>

Return.Sec=<b>{Return.Ti}</b><br><ol><li>{ReturnToProvider.Sec}</li><li>{Destroy.Sec}</li></ol>

ConfInfo.Sec=<b>{ConfInfo.Ti}</b><br>{ConfInfo.Intro.sec}<ol><li>{Include.Sec}</li><li>{Exclude.Sec}</li></ol>

Def.Sec=<b>{Def.Ti}</b><br><ol><li>{Def.Provider.sec}</li><li>{Def.Recipient.sec}</li><li>{Def.Confidential_Information.sec}</li></ol>

General.Sec=<b>{General.Ti}</b><br><ol><li>{BreachByDisclosure.Sec}</li><li>{Notice.Sec}</li><li>{Amend.Sec}</li><li>{GovtDemand.Sec}</li><li>{Dispute.Sec}</li><li>{Law.Sec}</li></ol>

Misc.Sec=<b>{Misc.Ti}</b><br><ol><li>{Counterpart.Sec}</li></ol>

CodersNote=English Language defaults (to be moved to the /US/EN/ folder)

Doc.Ti=Non-Disclosure Agreement

Why.Ti=Whereas:

Among.Ti/2=By and Between:

This.sec/2=This {Doc.Ti} (this "{Def.Agreement.sec}") is made as of {EffectiveDate.YMD} ("{Def.Effective_Date.sec}"), by and between the {_Parties}.

Why.Ti=Recitals

That.sec=In consideration of the mutual promises contained in {_this_Agreement} and other good and valuable consideration, the receipt and sufficiency of which is hereby acknowledged, the {_Parties} agree as follows:

By.Ti=Signature

Note=As with "Among," By assumes two parties but you can make more - By.secs={By.secs/3} or 4, etc.

By.0.sec=IN WITNESS WHEREOF, the {_Parties} have executed {_this_Agreement} as of the {_Effective_Date}.

CodersNote=Section Headings

Prime.Ti=Primary Terms

Convey.Ti=Conveying Confidential Information

Confide.Ti=Scope and Methods of Confiding Information

Use.Ti=Use of Information

IP.Ti=Intellectual Property Rights

Circulate.Ti=Circulation of Information by Recipient

Copy.Ti=Copies of Information Made by Recipient

Return.Ti=Return of Information by Recipient

ConfInfo.Ti=Confidential Information

Def.Ti=Definitions

General.Ti=General Terms

Misc.Ti=Miscellaneous Terms