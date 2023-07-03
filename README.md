# SocialMesh
SocialMesh is an innovative social media decentralized application (dApp) built on the Fantom Foundation blockchain. Its primary objective is to establish a platform that fosters vibrant communities by leveraging the power of blockchain technology. Here are the key features and functionalities of SocialMesh:

- Community Empowerment: When a community is created on SocialMesh, a billion unique tokens are minted specifically for that community. These tokens play a pivotal role in empowering and gamifying communities.
- Token Utility: The community tokens serve multiple purposes within the SocialMesh ecosystem. Firstly, they determine the voting power for community governance, ensuring that decision-making is fair and representative. Secondly, tokens are used to pay for various services within the community, such as advertising or commerce. Additionally, the tokens can be utilized as a form of payment for services, including jobs and gigs.
- Token Collection: Community tokens can be obtained through a reward system, where tokens are rewarded for providing assistance or engaging content within the community. Furthermore, an in-app marketplace facilitates the buying, loaning, and swapping of tokens, enabling users to acquire tokens through various means.
- Decentralized Communities: In SocialMesh, communities are owned collectively by every member of the community, rather than being controlled solely by the user who created them. This decentralized ownership structure ensures that decision-making power is distributed among community members.
- Autonomous Communities: SocialMesh communities operate autonomously, with no involvement from the SocialMesh team in their governance. This grants communities the freedom to establish their own rules and processes.
- Multiple Community Memberships: Users have the flexibility to be members of multiple communities simultaneously, allowing them to engage with diverse interests and networks.
- Unique Concept Communities: On the blockchain, there can only be one community for a particular concept. However, sub-communities and cliques can be formed within a community to cater to specific aspects or interests.

Overall, SocialMesh leverages blockchain technology to create an inclusive and engaging social media platform where communities can thrive, enabling users to actively participate, govern, and benefit from their collective experiences.

## How we built it
After conducting extensive research, we embarked on the project by designing the user interface (UI) using Figma. Once the UI design was finalized, we proceeded to develop the frontend of the application. For this purpose, we utilized React.js, Bootstrap, CSS, and WAGMI, ensuring a robust and visually appealing frontend implementation. The technologies used for our smart contract and backend include Solidity, Hardhat, TypeScript, Node.js, Express.js, and PostgreSQL.
- Choosing TypeScript as the primary backend language was driven by its benefits: enhanced code reliability through static typing, improved IDE support for productivity and readability, and compatibility with modern ECMAScript features across browsers.
- Solidity is an object-oriented programming language specifically created by the Ethereum Network team for constructing and designing smart contracts on blockchain platforms. It enables the creation of smart contracts that implement business logic and generate transaction records on the blockchain. We use this technology for our smart contract because Fantom is a Solidity-compatible chain and supports the Ethereum Virtual Machine (EVM).
- Hardhat is a versatile and JavaScript-based framework designed for Ethereum blockchain developers. It offers a wide range of features and functionalities to streamline the development of decentralized applications (dApps) on the Ethereum network. Hardhat was used in our project because it simplifies smart contract development by automating certain steps in our contract development and because it provides some helpful tools.
- Node.js, combined with Express.js as the chosen web framework, offers a robust and efficient solution for server-side development. The decision to use Node.js was primarily driven by its exceptional performance and scalability. Node.js utilizes an event-driven, non-blocking I/O model, enabling our application to handle a large number of concurrent connections efficiently. Furthermore, the ability to write both client-side and server-side code in JavaScript promotes code reuse and reduces context switching for developers. The extensive Node.js ecosystem, with its wide range of open-source libraries and modules available through npm, provides abundant resources for rapid development. Express.js, being a minimalist web framework, complements Node.js by offering essential web application functionalities and a flexible routing system, facilitating quick and efficient development of APIs and web applications.
- PostgreSQL was chosen as our database management system due to its renowned reliability, data integrity, and comprehensive feature set. Its robust relational model is ideal for applications with intricate data relationships and transactions. Compliance with ACID properties ensures consistent and reliable data. PostgreSQL's flexibility and extensibility enable us to work with diverse data types, including custom ones, tailoring the database to our project's specific needs. Furthermore, scalability features like table partitioning and replication support horizontal scalability and high availability as our application expands.
