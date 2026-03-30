# Assignment 01: Project Proposal

## 1. Project Description

My semester project is a web application called **Milly Maker Simulator**. The application is built for daily fantasy sports users who play tournament contests on DraftKings and FanDuel and want a better way to study lineup outcomes, contest structures, and winning roster patterns. A visitor would enter a simulator section, review contest settings, test lineup assumptions, and use an analysis section to study how simulated player rating ranges by position show up in Milly winning lineups. This proposal is built as one semester long project with a first prototype in Project 01 and a more polished MVP in Project 02. 

This project matters because large field DFS contests are difficult to study in an organized way. Many players rely on scattered opinions, screenshots, and memory instead of a single tool where they can test assumptions and review lineup trends in one place. My goal is to create a web application where users can simulate contest scenarios and study what tends to appear in tournament winning builds, especially from a positional rating standpoint. The purpose is to give DFS players a clearer way to think through lineup construction instead of relying on guesswork. 

The intended audience is serious DFS players, especially tournament players who care about lineup construction, contest selection, and large field strategy. The main user would be someone who already understands DFS basics and wants a more analytical tool for testing ideas and reviewing winning lineup patterns. This audience would care because the site is focused on tournament decision making instead of general fantasy advice. 

## 2. Feature Plan

### Project 01 (due Week 05)

1. **Homepage and project overview**  
   The site will include a homepage explaining what the simulator is, who it serves, and what users can do once they enter the application.

2. **DraftKings classic contest simulator**  
   The first working simulator will focus on one DraftKings large field classic contest format so the prototype has a clear and manageable scope.

3. **Contest settings panel**  
   Users will be able to view the basic contest structure, including salary cap assumptions, roster format, and simulation inputs tied to the selected contest type.

4. **Lineup simulation interface**  
   The prototype will include a page where users can enter player level assumptions and view simulated lineup outcome results.

5. **Results view**  
   The simulator will return a results section showing projected lineup performance and a small set of winning build signals.

6. **Positional rating analysis page**  
   The prototype will include an analysis section tracking which simulated rating ranges by position appear most often in Milly winning lineup constructions.

7. **Responsive layout and navigation**  
   The site will be organized in a way where users can move between the simulator and analysis pages on desktop and mobile devices.

### Project 02 (due Week 08)

1. **FanDuel support**  
   The application will expand beyond DraftKings and add FanDuel contest support with site specific roster and scoring considerations.

2. **Additional contest modes**  
   The simulator will expand beyond the first prototype contest flow and support more contest formats hosted by each site.

3. **Improved simulation controls**  
   Users will have more options for adjusting assumptions, comparing outputs, and reviewing scenario based changes.

4. **Expanded analysis dashboards**  
   The tracker section will grow into a deeper analysis area where users can compare position groups, lineup structures, and tournament winning tendencies.

5. **UI and UX refinement**  
   The MVP will place strong attention on layout, hierarchy, readability, navigation, and dashboard presentation so the application feels polished and easy to use.

6. **Deployment and final presentation polish**  
   The final version will be organized as a cleaner MVP with improved styling, clearer content structure, and stronger usability across the full project. 

## 3. Tools and Technologies

I plan to use **Visual Studio Code** as my code editor because it is the development environment I already use most often and it gives me a familiar workspace for writing, organizing, and editing project files. I chose it over other editors because I am already comfortable with its layout, terminal access, and file management, which should help me move through the build process with less friction. 

For the framework or development approach, I plan to build the project as a web application using **HTML, CSS, and JavaScript**, with room to organize the front end more formally if the application grows in complexity. I chose this approach because it gives me direct control over the interface and simulator behavior while keeping the first prototype achievable within the course timeline. Since the course stresses buildable scope and a working foundation for Project 01, starting with a simpler front end approach makes more sense than overbuilding early. 

For hosting and deployment, I plan to use **GitHub** for version control and either **GitHub Pages** or another simple hosting option to publish the site. I chose GitHub because it is already part of my course workflow, it gives me a clear record of project progress, and it provides an easy way to share my work through a URL. This also matches the course structure, since my proposal can be submitted through GitHub and later projects need to be accessible online.

For AI tools, I plan to use **ChatGPT** and **GitHub Copilot** for coding support, debugging, feature planning, and interface refinement. I chose these tools because they can help me move faster when I run into syntax issues, logic problems, or layout decisions, while still leaving the project direction and final choices in my hands.

Other tools may include **browser developer tools** for testing, **Git** for source control, and a design tool such as **Figma** for layout planning if needed. I may also use charting or visualization libraries later in the project if they improve the presentation of simulator results and lineup trend analysis. 

## 4. Risks and Unknowns

The biggest risk in this project is **scope**. A simulator covering every contest type across both DraftKings and FanDuel could become too large for the time available in this course. Because of this, my plan is to keep Project 01 focused on one core DraftKings classic contest flow and move broader site support, extra game modes, and deeper feature expansion into Project 02. This approach follows the course guidance for building a working foundation first and extending it later. 

Another risk is the **simulator logic itself**. I know the product direction I want, but there is still uncertainty around how far I can push contest logic, lineup assumptions, and scenario outputs within the time frame of the class. My plan is to begin with a simplified simulation model and build a usable front end first, then improve logic and complexity after the foundation is stable. 

A third unknown is the **analysis module**. I want to track which simulated player rating ranges by position appear in Milly winning lineups, but I may need to reduce the number of tracked variables in the prototype so the feature stays understandable and buildable. If needed, I will keep the first analysis page narrow and expand the data views later in Project 02. 

A fourth risk is **UI and UX scope**. I care a lot about making the application look polished, but design refinement can take up a large amount of development time. My plan is to prioritize structure, navigation, and usability in Project 01, then spend Project 02 improving visual hierarchy, styling, and the overall user experience. 
