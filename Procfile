web: voila --port=$PORT --no-browser --strip_sources=True --enable_nbextensions=True --MappingKernelManager.cull_interval=60 --MappingKernelManager.cull_idle_timeout=120 notebooks/appaissata.ipynb
heroku ps:scale web=1 -a <appaissata>
