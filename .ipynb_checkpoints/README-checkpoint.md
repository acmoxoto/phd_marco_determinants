phd-ico-macro-determinants/
├── README.md                      # Project overview, objectives, and dependencies
├── requirements.txt               # Python/R libraries and versions used
├── data/
│   ├── raw/                       # Raw datasets (ICO listings, ESG metrics, macroeconomic indicators)
│   │   └── ico_data_raw.csv       # Example: ICO campaign details, funding outcomes
│   ├── processed/                 # Cleaned/transformed datasets
│   │   └── ico_esg_clusters.csv   # Output from ESG and clustering experiments
│   └── documentation.md           # Data sources, cleaning steps, and variable definitions
├── experiments/
│   ├── esg_scoring/
│   │   ├── notebook.ipynb         # Code for ESG score calculation (scraping, NLP, scoring logic)
│   │   ├── data/                  # Scraped ICO project data (whitepapers, team info)
│   │   └── README.md              # Description of ESG methodology and relevance to ICO adoption
│   ├── fuzzy_clustering/
│   │   ├── notebook.ipynb         # FCM implementation (clustering macro-determinants like GDP, education)
│   │   ├── results/               # Cluster labels, silhouette scores, visualizations
│   │   └── README.md              # Explanation of clustering approach and macroeconomic drivers
│   └── tsne_visualization/
│       ├── notebook.ipynb         # t-SNE for dimensionality reduction of high-dimensional ICO data
│       ├── results/               # 2D/3D plots of clusters, perplexity optimization
│       └── README.md              # t-SNE parameterization and insights into ICO pattern recognition
├── results/
│   ├── esg_scores_summary.csv     # Aggregated ESG scores for ICO projects
│   ├── cluster_analysis.png       # FCM cluster visualizations
│   └── tsne_projection_3d.html    # Interactive t-SNE plots for exploration
└── paper_drafts/
    └── methodology.pdf            # Detailed description of experimental design and theoretical framework