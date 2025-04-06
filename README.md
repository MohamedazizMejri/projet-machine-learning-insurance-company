Afin de proposer des offres de contrats d’assurance habitation personnalisées, une assurance souhaite 
intégrer dans son système un modèle qui permet de prédire si un bâtiment aura un accident pendant la 
période d’assurance. Ainsi, nous lançons cette compétition afin de lui proposer le modèle de prédiction 
gagnant. Pour cela, nous mettons à votre disposition le dataset train_insurance.csv. Il est 
composé de 5012 observations décrites par 12 attributs descripteurs et une variable classe claim.   
Voici une brève description des différentes variables :  
• Customer Id : Le numéro d’identification du bénéficiaire  
• YearOfObservation : L’année d’observation de l’état du bâtiment 
• Insured_Period : La période d’assurance (1 : 1 ans, 0.5 : 6 mois) 
• Residential : Le bâtiment est-il résidentiel ? (1 : oui, 0 : non)  
• Building_Painted : Le bâtiment est-il peint ? (N : oui, V : non) 
• Building_Fenced : Le bâtiment est-il clôturé ? (N : oui, V : non) 
• Garden : Le bâtiment a-il un jardin ? (V : oui, O : non) 
• Settlement : La zone du bâtiment. (R : zone rurale, U : zone urbain) 
• Building Dimension : La taille du bâtiment en m2 
• Building_Type : Le type de bâtiment ('Fire-resistive', 'Non-combustible', 
'Ordinary', 'Wood-framed') 
• NumberOfWindows : Le nombre de fenêtres du bâtiment (without dans le cas de 0 fenêtre) 
• Geo Code : Le code géographique du bâtiment assuré 
• Claim : La variable classe (oui si le bâtiment a au moins une réclamation pendant la période 
d’assurance, et non si le bâtiment n’a pas eu de réclamation pendant la période d’assurance) 
