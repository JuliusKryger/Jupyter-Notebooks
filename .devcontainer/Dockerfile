# Use an official Jupyter datascience-notebook image as a parent image
FROM jupyter/datascience-notebook:latest

# Set the working directory to /home/jovyan/work
WORKDIR /home/jovyan/work

# Install the required Python package
RUN pip install ucimlrepo
RUN pip install kagglehub
# (Add any additional packages as needed)

# Make port 8888 available to the outside
EXPOSE 8888