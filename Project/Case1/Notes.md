# Case Study 1 - Freshippo: Data-Driven Business Model Inovation

## Introduction

Freshippo, criada em Xangai em 2016, reune os dois canais tradicionais de compras (supermercados / e-commerce) e algumas facilidades:

- Fresh food cooked in store to eat on the spot;
- By scanning QR code, the user could ask the app to carry the groceries home;
- Users can place orders online (as regular e-commerce platforms);

Lida com as tecnologias:

- Mobile Internet;
- Cloud Computing;
- Big Data;
- Artificial Inteligence;

## Data Driven Business Model

A tecnologia permitiu a coleta de grandes quantidades de dados. A top-level design architecture da Ali Cloud permitiu KPI específicos:

- the revenue from online transactions should be greater than that from offline transactions;
- each store should generate more than 5,000 orders per day online;
- the Freshippo app should be able to survive independently without support from other online traffic;
- the stores should offer 30-minute delivery while keeping logistics costs under control;

Os `target customers` são mulheres de 20 a 45 anos (*white-collar workers*) que usem a Alipay. Dados mostram que este grupo têm famílias ao seu cuidado, uma vida fast-paced e preferem fresh food. A aplicação é uma excelente escolha quando não se podem deslocar à loja física.

Foram rápidos a conquistar o mercado pois a secção de seafood nas lojas físicas era muito limpa e bem apresentada, aumentando ainda mais com a expansão dos boatos pelas redes sociais. As lojas de conveniência F2 (Fast and Fresh), aberta pela primeira vez em dezembro de 2017 serviram para combater o tempo dos office workers em filas de espera para o pequeno-almoço, almoço e chá da tarde. Os customers pedem na app e vão às lojas levantar e comer, sem espera adicional. Este tipo de loja tem uma área de 500m2 e servem customers localisados num raio de 500 metros.

Freshippo Cloud Supermarket, abril de 2018, oferecia produtos que não estavam nas lojas físicas, entregando produtos baseados nos dados recolhidos e nas necessidades dos clientes. Ofereciam o melhor valor em 10 categorias principais de produtos, as entregas noturnas, e os clientes exigiam entregas rápidas apenas quando não tinham preocupação com o preço.

Hexiaoma é um tipo de Freshippo que acaba por não ser semelhante: oferece a 1ª entrega grátis, até 3 kms de distância, mas a entrega pode ser de até 1 hora em vez dos 30 minutos. Além disso, não oferecem seafood, nem in-site preparation foods. Clientes reclamavam do tempo de espera. O site usa big data do Ali Baba.

Freshippo Nanxiang Store foi uma iteração de Fevereiro de 2018 que permitiu uma automação nas entregas in-store e na própria confeção de comida:

- Customers choose their seats at entrance
- Scan QR code to order dishes
- Track for robots to deliver dishes (40 seconds average)

No entanto, apesar da tecnologia, vários clientes reclamaram da falta de carisma na comida - precisavam de contacto mais humano.

## Data Driven Core Competencies

Business models criados a partir de tecnologias de ponta e mature data-processing.

### Data driven site selection

Dados dos profiles de Alipay ou de third-party platforms são usados para selecionar o local da store. Interessava:

- local de maior quantidade de transações e dinheiro por transação;
- quantidade de estacionamento, custo de arrendamento do espaço;
- Apesar da maioria dos locais serem em grandes centros, às vezes escolhiam locais remotos, pois os dados mostravam que foi a casa executiva de 500 companhias de fortuna;

### Online Traffic Guided by Physic stores

A aplicação permitiu converter o público do físico para o online:
    
- As stores físicas obrigavam a ter a aplicação para pagamento;
- Modelo físico e online têm o mesmo conjunto de produtos, da mesma qualidade;
- Tinham de usar a aplicação mesmo para order food para casa;
- Havia self-checkout nas lojas;
- Os customers podem pedir comida na loja, e podem comprar outras coisas enquanto a notificação de comida pronta não chega;

Como era tudo na aplicação, permitia que os dados dos utilizadores fossem coletados.

### Personalized Marketing

Os dados dos utilizadores podem ser usados para recomendações, marketing, festas entre crianças da mesma idade nas lojas ou enviar promoções a determinados utilizadores.

### Supply Chain Management

Supply Chain was managed with new technology and equipement. Supply Chain Management System (SCMS) was developed around the Alibaba Cloud Platform. Use of deep learning techniques to enhance the Supply Chain operations.

## Data-Driven Product Selection

The product selection would be based (before opening the store) on Alipay users and after it opens, would take no more than 2 months to the products fall into place.

Early 2018, Freshippo would already created 300 private-label brands (due to is R&D team). Products under the private-label brands were purchased through the "buyers system" directly to production bases. "Daily fresh" products were purchased via the supply chain that was built with local farms. For example, partner with fishing rights in Alaskan waters for king crabs.

After 2 months of opening a store, Freeshippo traked the sales of each SKU to see what were the products that must be stocked. It's 2 months because it was the conversion time of the custumers' ordering patterns.

Products of 3rd-party brands were selected via big data analysis, to make prices more reasonable they do not charge entry fees, and so on.

### Warehouse Management

There is two levels of Warehouses:

- Central Warehouse
    * Quality inspection
    * Product Standardization
    * Live Seafood Farming
    * Products delivered in bulk on pallets
- Store Warehouse
    * Responsible to get the "daily fresh" products
    * Products delivered in small packages

Warehouse management was also built on top of Alibaba systems. Freeshippo invented a real time pricing and inventory management, triggering promotions when, for example, the "daily fresh" products were on the shelves for almost one entire day. Also if some product was moving slowly between central / store warehous to the stores, a replanishment would be done, all according to the sales performance.

Daily fresh procusts were delivered from farms to store warehouses and the rest of the products were deliver in bulk on pallets by trucks from origin or suppliers to the central warehouse and then to the store warehouses.

System would take into account products that were not selling so much and the central warehouse would be noticed, to make promotions or automatic replenishment.

Every Product had an eletronic shelf label and a barcode and employees could identify products with inteligent devices.

### Store Operation

Since the products have a bar code, the employees could easily identify products and with the help of the system they could perform other tasks efficiently like receiving goods, shelving, order picking, packaging and distribution.

The store operation system was able to assign tasks to the employees that were accurate to the minute, ensuring balanced distribution of work and optimal human efficiency.

### Order Fulfillment

The product picking time for each employee was controlled by the system to stay less than 3 minutes. Transportation for the store warehouse and final package must be done under 3 minutes each as well. To ensure delivery in 30 min the delivery man has 21 minutes to do the job.

The whole order-generation process did not take more than 10 mins, due to system balanced distribution of work and technologies like conveyor belts hanging on store ceilings.

The product picking-time by each employee was controlled to stay within 3 minutes.
 
### Logistics and Distribution

Based on order time and address, the system optimized routes for the delivery man, combining different orders into delivery batches. 
This process included also information like order batch, batch category (normal / cold temperature), delivery men's familiarity with the distribution area and location at that given time.

Distribution on the Freeshippo Cloud Supermarket is done differently.
Orders would accumulate until a certain quantity and then the best route is computed. This allows the company to minimize the cost of these deliveries.

## Other Technology-Driven New Retailers (Competitors)

### Amazon Go

They eliminated cashier checkout ("take and go" policy). When you take a product from the shelf the app adds that product to a virtual shopping cart.
They had problems with this approach if more than 20 people were on the store putting and taking products from the shelves too fast. They solve the problem after a year and opened to the public.

### Unattended Convenience Stores and Unattended Shelves

China wanted to compete on this market and many convenience stores of this kind entered the market. However most of them could not compete with amazon go because the products use RFID labels which require the user to scan them, making this not a proper "take and go" store.

## The Future of Freeshippo

With 5G, more data sources would be found and more bussiness oportunities would also emerge.