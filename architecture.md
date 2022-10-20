A simple architecture to how to setup Master-Slave architecture.
## Create a slave node
  1. Go to Manage Jenkins -> Configure Global Security -> and enable TCP port for agent.
   <img width="313" alt="image" src="https://user-images.githubusercontent.com/48701982/197001650-303ca19f-c38e-453b-94bf-db11e5e3364c.png">
  2. Go to Manage nodes/Cloud -> add new node by specifying the working directory needed. Also, Label the node so that you can enable to execute jobs only when label expression matches the node.
  
   <img width="484" alt="image" src="https://user-images.githubusercontent.com/48701982/197001794-eb85a6ae-ad01-4687-a38a-b7dc54fe4240.png">

  3. Post creating the node, Jenkins will provide you the setup to start the slave node. Go to the working directory of your slave and setup the agent requirements.
      
   <img width="773" alt="image" src="https://user-images.githubusercontent.com/48701982/197001438-ab9d71ce-b818-4533-87a2-da7994b2f0aa.png">
  4. To run the project in slave node - specify the label expression in the project steps.
   <img width="400" alt="image" src="https://user-images.githubusercontent.com/48701982/197002380-cba87dc7-e907-436d-9028-e1803241ce8b.png">
  
  ## Jenikins CICD Pipeline
  
  <img width="658" alt="image" src="https://user-images.githubusercontent.com/48701982/197002915-a093f8f7-0847-419d-a679-72513fd0734b.png">


