idf_component_register(
	SRCS "main.c" "../telemetry/telemetry.c" "../telemetry/telemetry_esp32.c"
  INCLUDE_DIRS "."
	PRIV_INCLUDE_DIRS "../telemetry"
)
