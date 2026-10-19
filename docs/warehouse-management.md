# Case Study 02 · Warehouse Management and Stock Transfer

**Environment:** Academic SAP warehouse/inventory exercise, simulated company data.

## Business scenario

Transfer a quantity of finished goods from one location to another while tracking goods issue, goods in transit, goods receipt, and putaway.

## Documented workflow

| Stage | Observed change in course exercise |
| --- | --- |
| Starting inventory | Sending location: **250 units**; receiving location: **3 units** |
| Transfer quantity | **10 units** |
| After goods issue | Sending location decreases to **240 units**, while receiving location stays at **3 unrestricted units** and shows **10 units in transit** |
| After goods receipt | Receiving location increases from **3 to 13 units** |
| Warehouse putaway | **10 units** recorded as available in the target storage bin |

## Why it matters

A goods issue and a goods receipt are separate business events. During a transfer, goods may have left the sending location without yet becoming available at the receiving location. Proper tracking helps prevent double counting and enables inventory reconciliation.

## Learning outcomes

- Interpret stock balances by location and status.
- Follow the end-to-end logic of a stock transport process.
- Explain the difference between *on-order/in-transit* and *unrestricted-use* stock.
- Verify a warehouse process using recorded stock changes.

## Scope

All quantities refer to a **training scenario**. Technical document numbers and trainee-specific material IDs have been omitted. The case study summarizes the author's saved exercise answers; it is not a third-party warehouse implementation or a real business transaction.
