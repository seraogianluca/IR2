# Operational Structure

- Location of warehouses and inventory management policy

- Minimum order size

- Planning of delivery (monthly, weekly)

- Vendor rating model
- KPI
- Quality assurance policy and plan
- Manufacturing (Layout, Master Production Scheduling, Weekly production planning, Quality assurance implementation)
- Input to the RFP and RFQ

## Logistic and Warehouse

The factory in which we do the assembly is located in Italy.
In the same structure of the factory, there is the warehouse.
In this factory we receive the products from our suppliers, the final products is assembled and it's stocked in the warehouse. Periodically, a certain number of final product (robot + base accessory + power supply) is package and sent to the client.
Our warehouse is divided in two parts:

- One to store the final products
- One to store the suppliers

The warehouse is very important for our business.
In this area there are {warehouse_workers} people that deal with the operations in the warehouse: from storage to packaging.

### Inventory Managment

Incoming goods:

- supplies

Outcoming goods:

- Dolly X
- Molly X
- Dolly S
- Molly S

## Supplies

In order to assembly a robot we need the following mechanical and electronic components:

- Engine
- Wheels
- Frame
- Actuators (aspirator, mop)
- CPU
- Motherboard
- Sensors
- Body
- Accessories: bags, brush, ecc...
- Battery
- Power Supply

These components are provided by **external** suppliers for the following reason:

- suppliers have specialized research and know-how: the can provide us very high quality components

- future volume requirements are uncertain

- they can exploit better economy of scale

The assembly is full internal for two main reason:

- it's the way to guarantee an high quality of the product.

- we must install and configure the software by ourselves, in order to keep the secret.

We can divide all the suppliers in the following categories:

- Critical Products: the products that are customized for our company  (sensors, battery, body, power supply)

- Leverage Products: we need an high volume of these supplies but the suppliers are many.

For the first category there is one sourcing, we estabilished very detailed contracts with:

- a company that produces very accurate sensors, this company is at the forefront in this field.

- a company that produces durable battery and the power supply

- a company that produce in large scale the body and the frame of the robots using our indications for design and for material

For the second category there are multiple sources:

- several companies that produce hardware components: they provides us the motherboards and the CPUs

- several companies that produce accessories with common interfaces.

### Supplies cost

Common suppliers among the robot top of range.

| **Supply**       | **Characteristic**                         | **Cost per piece** | **Parts for robot** |
| ---------------- | ------------------------------------------ | ------------------ | ------------------- |
| Engine           |                                            | 50,00 €            | 1                   |
| Wheels           |                                            | 2,00 €             | 4                   |
| Frame            |                                            | 20,00 €            | 1                   |
| CPU              |                                            | 20,00 €            | 1                   |
| Motherboard      |                                            | 15,00 €            | 1                   |
| Proximity Sensor | Inductive Sensors without reduction factor | 5,00 €             | 10                  |
| Anti Fall Sensor |                                            | 2,50 €             | 2                   |
| Body             | Sideral Gray                               | 15,00 €            | 1                   |
| Battery          | 2600 mAh - 120 min of autonomy             | 10,00 €            | 1                   |
| Power Supply     | 3-5 h of charge                            | 20,00 €            | 1                   |
| **Totale**       |                                            | 213,00 €           |
