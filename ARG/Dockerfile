ARG version 
# version can not be accessed after from instruction, it duty is ony to supply version to FROM 
FROM almalinux: ${version:-8}
ARG COURSE = "Docker" \
    TRAINER = "siva kumar"

RUN echo "Trainer is ${TRAINER}"

CMD ["sleep", "200"]