# Bitgiant

## Project positioning
Bitgiant this is a peer-to-peer lending agreement that allows NFT holders to unlock erc-20 token liquidity by issuing their NFT as collateral.
## Solve what problem
Bitgiant is a platform that provides a liquidity lending market for NFT. The protocol is a combination of defi and NFT. This allows users to use the token in urgent need without having to bother to find a buyer or sell their NFT at a low price to attract buyers. They only need to mortgage their NFT, lend the token in urgent need, and then pay the interest as agreed. In addition, many users have a lot of high-value NFT, which is equivalent to having a lot of idle funds. Users can also use it for mortgage lending to make their own funds flow and avoid waste.
## characteristic

#### Asset packaging
Wnft (wrapped NFT) - deposit Mixed Assets (erc721, erc1155, erc20) and cast NFT.
#### loan
- Loan application - the borrower can apply for a loan and set conditions, such as capital (erc20), term, interest amount, etc
   A loan with a term of at least one day, guaranteed by wnft.
- No trust matching - the lender can provide funds for the loan request without trust. Once countersigned, both the lender and the borrower can arrange loans for on chain settlement.
- Borrower's note - when clearing the loan on the chain, the capital amount is paid to the borrower's address, the encapsulated assets and mortgage in wnft are transferred to the lender's address, and the borrower receives the borrower's note (erc721), indicating its claim for the assets when repaying the loan.
- No prepayment penalty - the loan can be repaid at any time to recover the assets entrusted on the agreement chain.
####   to loan
- Untrustworthy matching - the borrower can settle the loan by accepting the loan offer in an untrustworthy manner because the lender has digitally signed the terms of the offer and approved the financing amount of these terms in accordance with the pawn agreement.
- Credit note - when liquidating a chain loan, the lender transfers the amount of funds from the wallet to the borrower's wallet and receives a credit note (erc721), which represents its claim on wnft, which encapsulates the loan mortgage assets (and therefore claims on the assets themselves) if the loan defaults.
- Untrusted creditor's rights - the simple logic embedded in the pawn agreement determines whether the loan is in default. If the financing amount + interest amount is not paid at the end of the loan term, anyone can apply for the loan. Wnft, as well as assets that provide security for defaulted loans, are transferred through the chain to the address where the lender's notes are held.




