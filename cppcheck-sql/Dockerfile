FROM ilssim/cmake-boost-qt5:latest
RUN apt-get -y update && apt-get install -y --no-install-recommends \
	cppcheck                                \
	libmysqlcppconn-dev                     \
	sqlite3                                 \
	libsqlite3-dev                       && \
	rm -rf /var/lib/apt/lists/*

