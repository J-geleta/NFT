\documentclass{article}
\usepackage{hyperref}

\title{Notafckingthing - NFT Minting Website}
\author{J-geleta}
\date{}

\begin{document}

\maketitle

\section{Introduction}
Welcome to the Notafckingthing NFT minting website! This project pokes fun at the impermanence of metadata associated with first-generation NFT contracts. It is integrated with the Solana blockchain and uses Metaplex's candy machine for minting unique tokens.

\section{Project Overview}
\begin{itemize}
    \item \textbf{Website:} \url{https://notafckingthing.com/}
    \item \textbf{GitHub Repository:} \url{https://github.com/J-geleta/NFT}
    \item \textbf{Blockchain:} Solana
    \item \textbf{Minting Mechanism:} Metaplex's candy machine
\end{itemize}

\section{Features}
\begin{itemize}
    \item Minting of NFTs with 7 potential traits of varying rarity.
    \item Integration with the Solana blockchain.
    \item Randomized minting process to ensure uniqueness of each token.
\end{itemize}

\section{Technical Details}
\subsection{Technology Stack}
\begin{itemize}
    \item \textbf{Frontend:} HTML, CSS, JavaScript
    \item \textbf{Backend:} Node.js, Express.js
    \item \textbf{Blockchain:} Solana
    \item \textbf{Smart Contract:} Metaplex's Candy Machine
\end{itemize}

\subsection{Setup Instructions}
To run this project locally, follow these steps:

\begin{enumerate}
    \item Clone the repository:
    \begin{verbatim}
    git clone https://github.com/J-geleta/NFT.git
    \end{verbatim}
    
    \item Navigate to the project directory:
    \begin{verbatim}
    cd NFT
    \end{verbatim}
    
    \item Install dependencies:
    \begin{verbatim}
    npm install
    \end{verbatim}
    
    \item Configure environment variables in a \texttt{.env} file:
    \begin{verbatim}
    REACT_APP_SOLANA_NETWORK=mainnet-beta
    REACT_APP_CANDY_MACHINE_ID=<Your Candy Machine ID>
    REACT_APP_TREASURY_ADDRESS=<Your Treasury Address>
    \end{verbatim}
    
    \item Start the development server:
    \begin{verbatim}
    npm start
    \end{verbatim}
\end{enumerate}

\subsection{Minting Process}
The minting process is designed to be random, ensuring each token has a unique combination of traits. There are 7 potential traits, each with varying rarity levels. The randomness is managed by the smart contract on the Solana blockchain, integrating Metaplex's candy machine.




\end{document}
