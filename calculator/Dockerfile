FROM aspnetbase:beta4
ADD /src /app
WORKDIR /app
RUN ["dnu", "restore"]
ENV URLOptimizerJobs=http://optim1:5004/api/Jobs/
CMD ["dnx", ".", "run"]
