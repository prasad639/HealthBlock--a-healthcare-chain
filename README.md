
HealthBlock Website
Project Overview
HealthBlock is a blockchain-based website designed for securely storing and managing patient data. The project utilizes Ethereum blockchain for decentralized and secure data storage. Truffle and Ganache are used to set up a local blockchain environment for development, while IPFS (InterPlanetary File System) is employed to store data and create links for patient data files.

The primary functionalities include the secure storage of patient data on the blockchain, the ability for patients to grant and revoke access to their medical records, and controlled access for doctors. Doctors can only access the patient data for whom they have been granted access, and they can edit the relevant information. Once the treatment is completed, access is automatically revoked.

The front-end of the HealthBlock website is developed using React and other web technologies to provide a user-friendly and responsive interface.

Features
Blockchain-based Storage: Patient data is stored securely on the Ethereum blockchain, ensuring immutability and decentralization.

Local Development Environment: Truffle and Ganache are used to set up a local blockchain environment, making development and testing efficient.

IPFS Integration: IPFS is utilized for storing data and generating links for patient data files, providing a decentralized and efficient way to manage files.

Access Control: Patients have the ability to grant and revoke access to their medical records, ensuring privacy and control over their data.

Doctor Access: Doctors can access and edit patient data only for the patients to whom they have been granted access.

Automatic Access Revocation: Once the treatment is completed, access to patient data is automatically revoked to maintain data security.

Technologies Used
Ethereum Blockchain
Truffle
Ganache
IPFS
React
Other web technologies
Getting Started
Follow these steps to set up the HealthBlock project locally:

Clone the repository: git clone https://github.com/yourusername/healthblock.git

Install dependencies:

bash
Copy code
cd healthblock
npm install
Set up the local blockchain environment using Truffle and Ganache.

Deploy the smart contracts to the local blockchain:

css
Copy code
truffle migrate --reset
Start the React application:

sql
Copy code
npm start
Access the HealthBlock website at http://localhost:3000 in your web browser.
