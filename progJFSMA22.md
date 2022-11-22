
## Programme des JFSMA'22</h2>
```mermaid
stateDiagram-v2
    [*] --> CreateRequest
    CreateRequest --> WaitMsg
    WaitMsg --> handleRefuse : refuse
    handleRefuse --> WaitMsg
    WaitMsg --> handleAgree : agree
    state forkAgree   <<fork>>
    handleAgree --> forkAgree
    forkAgree --> handleInform
    forkAgree --> WaitMsg
    handleInform --> handleAllResult : all results
    handleAllResult --> [*]
    
  
Voici le programme des JFSMA'22 pour les journées de [Lundi](#lundi), [Mardi](#mardi) et [Mercredi](#mercredi).

<a name="lundi">.</a>

|                                                                                              | <div style="color:#000;background-color:#ff9;"> LUNDI 27 JUIN </div>                                                                                                                                                |
|:---------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <div style="background-color:#FDA;">**14h45**</div>                                          | <div style="color:#000;background-color:#FDA;">**Mot d'accueil**</div>                                                                                                                                              |
| <div style="background-color:#DEF;color:#00E;">**Session 1**<br/>Lundi<br/>15h-16h15</div>   | <div style="background-color:#DEF;color:#00E;">**Résolution collective de problèmes, coordination, travail en équipe**<br/> <span style="color:#E70;">*(Prés. de session : Grégory Bonnet)*</span><br/>&nbsp;</div> |
| **15h00 - 15h35**<br/> *Prés. longue*                                                        | Coordination de trajectoires 4D par optimisation distribuée dans la gestion du trafic aérien sans pilote.<br/>*Gauthier Picard*                                                                                     |
| **15h35 - 16h10**<br/> *Prés. longue*                                                        | Échange de tâches pour la réduction de la durée moyenne de réalisation.<br/>*Ellie Beauprez, Anne-Cecile Caron, Maxime Morge and Jean-Christophe Routier*                                                           |
|                                                                                              | <div style="text-align:center;color:#000;background-color:#FDA;">*( Pause )*</div>                                                                                                                                  |
| <div style="background-color:#DEF;color:#00E;">**Session 2**<br/>Lundi<br/>16h45-18h15</div> | <div style="background-color:#DEF;color:#00E;">**Démonstrations et posters**<br/> <span style="color:#E70;">*(Prés. de session : Nicolas Sabouret)*<br/>&nbsp;</div>                                                |
| **16h45 - 17h00**<br/> *Démo*                                                                | Modélisation et simulation multi-agents pour la gestion des tâches entre véhicules et infrastructures dans le cadre de la ville intelligente.<br/>*Emmanuelle Grislin and Hamza Ouarnoughi*                         |
| **17h00 - 17h15**<br/> *Démo*                                                                | Maison Collaboratives.<br/>*Julien Cumin, Fano Ramparany, Iago Felipe Trentin and Olivier Boissier*                                                                                                                 |
| **17h15 - 17h30**<br/> *Démo*                                                                | Modélisation Multi-Agent pour les Réseaux Énergétique Insulaires.<br/>*Ihab Taleb, Guillaume Guerard, Nga Nguyen and Frédéric Fauberteau*                                                                           |
| **17h30 - 17h45**<br/> *Démo*                                                                | Une approche collaborative pour la recherche de places de stationnement.<br/>*Jean-David Collard, Erick Stattner and Panagiotis Gergos*                                                                             |
| **17h45 - 17h55**<br/> *Poster*                                                              | Comment les échecs de preuve peuvent aider à la correction de spécifications erronées de Systèmes Multi-Agents.<br/>*Bruno Mermet and Gaële Simon*                                                                  |
| **17h55 - 18h05**<br/> *Poster*                                                              | Apprentissage profond & systèmes multi-agents - Application à la segmentation d'images médicale.<br/>*Bennai Mohamed Tahar, Zahia Guessoum, Cormier Stéphane, Smaine Mazouzi and Lyse Gallay*                       |
| **18h05 - 18h15**<br/> *Poster*                                                              | Architecture SMA/RàPC enrichie d'outils d'aide à la décision pour prédire les risques en chirurgie.<br/>*Bruno Perez, Christophe Lang, Julien Henriet, Laurent Philippe and Frédéric Auber*                         |

-----
<a name="mardi">.</a>

|                                                                                              | <div style="color:#000;background-color:#ff9;"> MARDI 28 JUIN </div>                                                                                                                                               |
|:---------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <div style="background-color:#DEF;color:#00E;"><b>9h00-10h00</b><br/>&nbsp;<br/>&nbsp;</div> | <div style="background-color:#DEF;color:#00E;">**Conférencier invité JFSMA**<br/> <span style="color:#E70;">*(Prés. de session : Valérie Camps)*</span><br/>&nbsp;</div>                                           |
|                                                                                              | **From Smart to Autonomous (Cities, Homes, and Everything) : Opportunities and Challenges<br/>*[Franco Zambonelli](https://ci.mines-stetienne.fr/pfia2022/invites/#Franco_Zambonelli)***                           |
|                                                                                              | <div style="text-align:center;color:#000;background-color:#FDA;">*( Pause )*</div>                                                                                                                                 |
| <div style="background-color:#DEF;color:#00E;">**Session 3**<br/>Mardi<br/>10h30-11h30</div> | <div style="background-color:#DEF;color:#00E;">**Négociation multi-agent, consensus**<br/> <span style="color:#E70;">*(Prés. de session : Flavien Balbo)*</span><br/>&nbsp;</div>                                  |
| **10h30 - 11h05**<br/> *Prés. longue*                                                        | Un protocole de concessions monotones pour la formation distribuée de coalitions.<br/>*Josselin Guéneron and Grégory Bonnet*                                                                                       |
| **11h05 - 11h30**<br/> *Prés. courte*                                                        | Allocation par enchères et planification hiérarchique pour un système multirobot, application au cas de la chasse aux mines sous-marines.<br/>*Antoine Milot, Estelle Chauveau, Simon Lacroix and Charles Lesire.* |
|                                                                                              | <div style="text-align:center;color:#000;background-color:#FDA;">*( Pause Déjeuner )*</div>                                                                                                                        |
| <div style="background-color:#DEF;color:#00E;">**Session 4**<br/>Mardi<br/>14h45-16h00</div> | <div style="background-color:#DEF;color:#00E;">**Communication**</span><br/> <span style="color:#E70;">*(Prés. de session : Laurent Vercouter)*</span><br/>&nbsp;</div>                                            |
| **14h45 - 15h20**<br/> *Prés. longue*                                                        | Spécificité de l'argumentation scientifique dans un débat.<br/>*Louise Dupuis de Tarlé, Gabriella Pigozzi and Juliette Rouchier*                                                                                   |
| **15h20 - 15h55**<br/> *Prés. longue*                                                        | Transmission de connaissances et sélection.<br/>*Yasser Bourahla, Manuel Atencia and Jérôme Euzenat.*                                                                                                              |
|                                                                                              | <div style="text-align:center;text-align:centercolor:#000;background-color:#FDA;">*( Pause )*</div>                                                                                                                |
| <div style="background-color:#DEF;color:#00E;">**Session 5**<br/>Mardi<br/>16h30-17h40</div> | <div style="background-color:#DEF;color:#00E;">**Émergence, auto-organisation**</span><br/> <span style="color:#E70;">*(Prés. de session : à venir)*</span><br/>&nbsp;</div>                                       |
| **16h30 - 17h05**<br/> *Prés. longue*                                                        | P-ADRIP : un système multi-agent auto-organisateur pour la prévision du trafic routier.<br/>*Ha-Nhi Ngo, Elsy Kaddoum, Marie-Pierre Gleizes, Jonathan Bonnet and Anaïs Goursolle*                                  |
| **17h05 - 17h40**<br/> *Prés. longue*                                                        | Estimation de données environnementales manquantes sans déploiement de capteurs supplémentaires : le système HybridIoT.<br/>*Davide Andrea Guastella, Valérie Camps and Marie-Pierre Gleizes.*                     |

-----
<a name="mercredi">.</a>

|                                                                                                 | <div style="color:#000;background-color:#ff9;"> MARDI 28 JUIN </div>                                                                                                                                                    |
|:------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <div style="background-color:#DEF;color:#00E;">**Session 6**<br/>Mercredi<br/>10h30-12h05</div> | <div style="background-color:#DEF;color:#00E;">**Simulation, modélisation**</span><br/> <span style="color:#E70;">*(Prés. de session : Bruno Mermet)*</span><br/>&nbsp;</div>                                           |
| **10h30 - 11h05**<br/> *Prés. longue*                                                           | Dairy Health Manager : un simulateur multi-agents flexible pour l'étude des maladies des animaux d'élevage.<br/>*Philippe Gontier, Nathalie Bareille and Sébastien Picault.*                                            |
| **11h05 - 11h40**<br/> *Prés. longue*                                                           | Méta-modèle d'agent pour la génération de comportements variables induits par des modèles cognitifs modulaires.<br/>*Tristan de Blauwe, Domitile Lourdeaux and Nicolas Sabouret.*                                       |
| **11h40 - 12h05**<br/> *Prés. courte*                                                           | La modélisation Agent pour sensibiliser aux Solutions Fondées sur la Nature pour gérer les inondations.<br/>*Franck Taillandier, Annabelle Moatty, Corinne Curt, Pascal Di Maiolo, Bruno Beullac and Pénélope Brueder.* |
|                                                                                                 | <div style="text-align:center;color:#000;background-color:#FDA;">*( Pause Déjeuner )*</div>                                                                                                                             |
| <div style="background-color:#DEF;color:#00E;">**Session 7**<br/>Mercredi<br/>14h45-16h15</div> | <div style="background-color:#DEF;color:#00E;">**Session jeunes chercheurs**</span><br/> <span style="color:#E70;">*(Prés. de session : Emmanuel Adam)*</span><br/>&nbsp;</div>                                         |
| **14h45 - 15h00**                                                                               | *Aymeric Henard*, Réalité Augmenté et interfaces tangibles pour superviser et interagir avec les essaims de robots                                                                                                      |
|                                                                                                 | *Hector Roussille*, Multi-Agent Reinforcement Learning quantifying uncertainties in blockchain systems                                                                                                                  |
|                                                                                                 | *Maëlle Beuret*, Modèle d'animation comportementale de groupes d'agents comme moteur d'une plateforme de jeux sérieux                                                                                                   |
| **15h10 - 15h25**                                                                               | *Paul Breugnot*, Distribution et Synchronisation des Simulations de Systèmes Multi-Agents                                                                                                                               |
|                                                                                                 | *Mathias Déhais*, Preuve formelle de systèmes multi-agents stochastiques à l'aide de GDTs                                                                                                                               |
|                                                                                                 | *Florian Cogoni*, Approche participative transdisciplinaire pour la modélisation multi-agents appliquées à la biologie cellulaire                                                                                       |
| **15h35 - 15h50**                                                                               | *Sylvain Lapeyrade*, Raisonnements ontologiques en temps réel pour l'intelligence artificielle des personnages non joueurs dans les jeux vidéo                                                                          |
|                                                                                                 | *Juliette Grosset*, Stratégies d'Intelligence Collective pour des Véhicules Industriels Autonomes Efficaces                                                                                                             |
|                                                                                                 | *Arthur Baudet*, Architecture de Sécurité pour Système Multi-Agents Embarqués                                                                                                                                           |


