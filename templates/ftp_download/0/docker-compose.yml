version: "2"
services:
    ftp_download:
        build: .
        image: ftp_download:${FTP_DOWNLOAD_TAG}
        ports:
            - ${port}
        environment:
            - DATABASE_URL: ${DATABASE_URL}
        #volumes:
        #    - /var/run/postgresql:/var/run/postgresql
