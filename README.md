# DAPP PROJECT: Supply chain management with Smart Contract

With the help of smart contracts, this project will overcome traceability issues in supply chain management, so for instance, a textile manufacturer will use raw materials like cotton, flax, bamboo fibers, etc., for making cotton yarns. When these yarns are prepared, the company prepares fabrics with the help of the yarns, then after quality check, the company processes the fabric and sends it to the Cloth Producer (Garment Factory) to make garments using the various fabrics with the quality check process. Then, all garments like pants, T-shirts, or shirts are sent to department stores like Wal-Mart and Costco for whole-sale.
The textile company has a digital contract with the cloth producer, and the cloth producer has a digital contract with the wholesale store.


## What problem does this Dapp solve?

We will be able to solve traceability problems in supply chain management using this Dapp, so that suppliers, producers, and buyers all know exactly where their products are at all times.

## What is it best implemented on a blockchain?

Because blockchain uses smart contact to make digital contacts between the different parties involved, it is the best implementation on blockchain. As a result, these contracts become immutable and trustworthy. The latest progress can be checked by everyone, and every transaction becomes fair and trust-worthy and everyone gets paid right away for their hard work.

## Diagram
![](docs/diagram.PNG)

## Name of Contracts

 - contracts 	
	 - access/ 		
		 - roles/ 			
			 - Roles.sol
			 - TextileRole.sol
			 - ProducerRole.sol
			 - QualityCheckerRole.sol
			 - StoreRole.sol
	 - base/ 		
		 - SupplyChain.sol 	
	 - core/ 		
		 - Ownable.sol

## Smart Contract Overview

| CRITERIA   | MEETS SPECIFICATIONS |  Status |
|:-------|:--------|:--------:|
| SupplyChain.sol contains required tracking functions. | Smart contract implements functions to track.<br>For example:<br>- Product ID<br>- Product UPC<br>- Origination Information<br>- Textile Company<br>- Other Organization info<br>- Longitude & Latitude of geo coordinates<br>- Product notes  | :ok_hand: |
| Ownable.sol contains required functions that establish owner and the transfer of ownership. | Ownable.sol has required functions that establish owner and the transfer of ownership.  | :ok_hand: |
| StoreRole.sol contains required functions that manage the Store role. | StoreRole.sol has required functions that manage the Store role.  | :ok_hand: |
| ProducerRole.sol contains required functions that manage the Cloth Producer role. | ProducerRole.sol has required functions that manage the Cloth Producer role.  | :ok_hand: |

## Functionality

·----------------------------------------|----------------------------|-------------|----------------------------·
| Solc version: 0.6.12+commit.27d51765 · Optimizer enabled: false · Runs: 200 · Block limit: 6718946 gas │
·········································|····························|·············|·····························
| Methods │
··················|······················|··············|·············|·············|··············|··············
| Contract · Method · Min · Max · Avg · # calls · usd (avg) │
··················|······················|··············|·············|·············|··············|··············
| Migrations · setCompleted · - · - · 28660 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · addConsumer · - · - · 47989 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · addQualityChecker · - · - · 47943 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · addTextile · - · - · 47975 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · addProducer · - · - · 47987 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · fabricAuditItem · - · - · 53756 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · fabricCuttingItem · - · - · 73087 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · fabricPrepareItem · - · - · 214704 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · fabricProcessItem · - · - · 30407 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothSewingItem · - · - · 99488 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothBuyItem · - · - · 72463 · 1 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothCertifyItem · - · - · 53696 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothCreateItem · - · - · 121495 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothPackItem · - · - · 32688 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothProduceItem · - · - · 100619 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| SupplyChain · clothSellItem · - · - · 52723 · 2 · - │
··················|······················|··············|·············|·············|··············|··············
| Deployments · · % of limit · │
·········································|··············|·············|·············|··············|··············
| Migrations · - · - · 221335 · 3.3 % · - │
·········································|··············|·············|·············|··············|··············
| SupplyChain · - · - · 3750616 · 55.8 % · - │
·----------------------------------------|--------------|-------------|-------------|--------------|-------------·

