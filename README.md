# Data AI Customer Churn reference implementation

This project is part of the [IBM Data and AI reference architecture](https://ibm-cloud-architecture.github.io/refarch-data-ai-analytics/) and defines an interesting use case as solution implementation.

The goals of this implementation is to illustrate how to build an intelligent application using:

* Data Ingestion and Organization
* Model Development and Deployment
* Batch Scoring
* Model MOnitoring
* Cognitive service like Tone Analyzer and Chatbot
* Integrate with Customer Data base and unstructured data to build a customer churn predictive scoring model
* Deploy and monitor the model

For better reading experience go to [the book view.](http://ibm-cloud-architecture.github.io/refarch-ai-data-customer-churn)


## Building this booklet locally

The content of this repository is written with markdown files, packaged with [MkDocs](https://www.mkdocs.org/) and can be built into a book-readable format by MkDocs build processes.

1. Install MkDocs locally following the [official documentation instructions](https://www.mkdocs.org/#installation).
1. Install Material plugin for mkdocs:  `pip install mkdocs-material` 
2. `git clone https://github.com/ibm-cloud-architecture/refarch-ai-data-customer-churn.git` _(or your forked repository if you plan to edit)_
3. `cd refarch-ai-data-customer-churn`
4. `mkdocs serve`
5. Go to `http://127.0.0.1:8000/` in your browser.

### Pushing the book to GitHub Pages

1. Ensure that all your local changes to the `master` branch have been committed and pushed to the remote repository.
   1. `git push origin master`
2. Ensure that you have the latest commits to the `gh-pages` branch, so you can get others' updates.
	```bash
	git checkout gh-pages
	git pull origin gh-pages
	
	git checkout master
	```
3. Run `mkdocs gh-deploy` from the root refarch-ai-data-customer-churn directory.
