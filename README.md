# 8645-computer-infrastructure
**by Joseph Benkanoun**

<img src="https://github.com/ianmcloughlin/2425_computer_infrastructure/blob/main/img/cloud.jpeg" alt="Cloud" width="600"/>

Repository for the 2024 [Computer Infrastructure](https://www.gmit.ie/computer-infrastructure) module as part of the [Higher Diploma in Science in Data Analytics](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics) at ATU. 

The purpose of this assessment is to develop the ability to:
> *1. Use, configure, and script in a command line interface environment.*
> *2. Manipulate and move data and code using the command line.*
> *3. Compare commonly available software infrastructures and architectures.*
> *4. Select appropriate infrastructure for a given computational task.*

The assessment of this module comprised of two components:

- the tasks
- the project

### The Tasks

Over the course of the tasks, I gained experience in how to work directly in a command line environment. I used <code>mkdir</code> to create directories, <code>touch</code> to create files, and navigated among them all using commands such as <code>cd</code>, <code>ls</code>, and operators like <code>..</code>.

I learned how to use the <code>date</code> command, appending the output directly to a file using <code>>></code>, while formatting the output using a variety of <code>%</code> operators. Utilising <code>wget</code>, I fetched data from remote sources and saved it in timestamped files. Using a bash script, I created a file called <code>weather.sh</code> that wrapped everything from the previous steps into a script that could be executable from the command line. 

An outline of all tasks and how I approached them can be found in my Jupyter Notebook [weather.ipynb](https://github.com/JBnkn/8645-computer-infrastructure/blob/main/weather.ipynb).

### The Project

The project entailed setting up a **GitHub Actions Workflow** that would apply the knowledge learned in the tasks to automate <code>weather.sh</code> and set it to run daily.

The project component can be found within my <code>.github/workflows</code> folder. The automated outputs can be found under <code>data/weather</code>.