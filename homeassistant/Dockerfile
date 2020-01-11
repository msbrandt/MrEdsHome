FROM python
RUN adduser homeassistant

RUN python3 -m pip install homeassistant
ENTRYPOINT ["hass", "--open-ui"]