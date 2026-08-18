ARG VERSION
FROM almalinux:${VERSION:-9}
ARG name="Vinayraj" \
    email="vinnimudhiraj918@gmal.com"
ENV name=${name} \
    email=${email}
RUN echo "name: ${name}, emil: ${email}, Version: ${VERSION}" 
CMD ["sleep", "1000"]