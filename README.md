# ciphermail-mailencryption
RUN apt-get update && apt-get install -y \
	postfix \
	openjdk \
	openjdk-7-jre-headless \
	ant \
	ant-optional \
	mktemp \
	wget \
	libsasl2-modules \
	symlinks \
	&& rm -rf /var/lib/apt/lists/*
