\documentclass{article}

\title{Environmental Setup - Google Colab Projects}
\author{Your Name}
\date{\today}

\begin{document}

\maketitle

\section{Getting Started}

To begin using Google Colab for your projects, follow the steps below:

\begin{enumerate}
  \item \textbf{Open Google Colab}: Open your web browser and navigate to \url{https://colab.research.google.com/}.
  \item \textbf{Sign in with your Google Account}: If you're not already signed in, click on the "Sign in" button in the top-right corner and enter your Google account credentials.
  \item \textbf{Create a New Notebook}: In the Colab home page, click on "New Notebook" to create a new notebook file. Alternatively, you can upload an existing notebook from your computer or import a notebook from Google Drive or GitHub.
  \item \textbf{Choose a Runtime}: Colab provides two types of runtimes: CPU and GPU. For projects involving intensive computations, it's recommended to use the GPU runtime. You can select the desired runtime by navigating to the "Runtime" menu and choosing "Change runtime type." Select the appropriate hardware accelerator and click "Save."
  \item \textbf{Set Up the Environment}: Colab comes with many pre-installed libraries, but if you need additional packages, you can install them using the \texttt{!pip install} command within a code cell in your notebook. Note that any packages installed using this method will only persist for the duration of the current session. To ensure the installation persists for future sessions, you can use the \texttt{!pip install} command along with the \texttt{-q} and \texttt{--upgrade} flags.
  \item \textbf{Upload and Access Data}: If your project requires external datasets, you can upload them to Colab by using the file upload button in the sidebar. Alternatively, you can mount your Google Drive and access files from there. To mount your Google Drive, you can use the following code snippet:
  \begin{verbatim}
    from google.colab import drive
    drive.mount('/content/drive')
  \end{verbatim}
  \item \textbf{Save and Share Your Work}: Colab notebooks are automatically saved in your Google Drive. You can also download a copy of the notebook to your local machine by navigating to "File" > "Download .ipynb". To share your work with others, you can use the "Share" button to generate a link or invite collaborators.
\end{enumerate}

\section{Examples}

Google Colab provides a vast collection of example notebooks to help you get started with various topics, including machine learning, data analysis, and visualization. You can access these examples by navigating to the "File" > "Open notebook" > "Examples" menu in Colab.

Here are a few popular examples to explore:

\begin{itemize}
  \item \textbf{Introduction to Colab}: This notebook provides an overview of Colab's features and capabilities. Link: \url{https://colab.research.google.com/notebooks/intro.ipynb}
  \item \textbf{TensorFlow 2.0 Tutorials}: A series of notebooks introducing TensorFlow 2.0 and various machine learning concepts. Link:
