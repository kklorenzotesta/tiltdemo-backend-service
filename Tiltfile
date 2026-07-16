username = os.environ.get("USER")

defs = load_dynamic("./Tiltfile.definitions")

defs["setup"](
  namespace=username + "-backend-service",
  livereload=True
)
