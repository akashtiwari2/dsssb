# Three-variable K-map
Introduced31Oct2026; application pending.
Priority evidence: inspected P24 Q13 on Boolean minimisation, not frequency claim.
Notation: xy means AND; + means OR; x' means NOT x. Sigma m lists binary input indices for which output1; xyz uses x as most significant bit.
Grid rows x=0/1; columns yz in Gray order00,01,11,10.
Index grid:
x0:0 1 3 2
x1:4 5 7 6
Mark listed indices1 and others0. Group rectangular blocks of1,2,4,8 adjacent1s; use largest valid groups, cover all1s, overlaps allowed. First/last columns adjacent; diagonals not adjacent. No0 allowed in groups (no don't-cares in this question).
Keep variables constant within group:0 -> complemented,1 -> normal; remove changing variables. OR resulting terms.
Example group indices0(000),2(010) -> x'z' because y changes.
Pending K01, historical PYQ paraphrased: F(x,y,z)=Sigma m(0,2,4,5,6).
A z+x'y'; B z'+xy'; C z+x'y; D z'+xy.
Source: https://www.adda247.com/jobs/wp-content/uploads/sites/13/2026/06/02154459/DSSSB-TGT-Computer-Science-Official-Paper-Held-On_-07-Feb-2024-Shift-2-Eng.pdf ; first DisciplineQ13; ID630680598443; physicalp41. Third-party reproduction inspected earlier; final official key not verified.
Explain chosen groups, not just letter. Also R04:+10% then-10%; R05:ord('C'). All pending. Target4minutes is coaching allowance, not official per-question limit.
