################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccs6/ccsv6/tools/compiler/c5500_4.4.1

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./aic3204.obj" \
"./aic3204_init.obj" \
"./ezdsp5535_aic3204_dma.obj" \
"./iir.obj" \
"./main.obj" \
"./print_number.obj" \
"./window.obj" \
"../lnkx.cmd" \
"../c55xx_csl/lib/55xdspx_r3.lib" \
"../c55xx_csl/lib/cslVC5505.lib" \
"../lib/ezdsp5535bsl.lib" \
$(GEN_CMDS__FLAG) \
-llibc.a \
-lrts55h.lib \
-lcslVC5505.lib \
-lrts55x.lib \
-lezdsp5535bsl.lib \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include c55xx_csl/lib/subdir_vars.mk
-include lib/subdir_vars.mk
-include subdir_rules.mk
-include c55xx_csl/lib/subdir_rules.mk
-include lib/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
NoiseRemoval\ Sim.out \

EXE_OUTPUTS__QUOTED += \
"NoiseRemoval Sim.out" \

BIN_OUTPUTS += \
NoiseRemoval\ Sim.hex \

BIN_OUTPUTS__QUOTED += \
"NoiseRemoval Sim.hex" \


# All Target
all: NoiseRemoval\ Sim.out

# Tool invocations
NoiseRemoval\ Sim.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: C5500 Linker'
	"C:/ti/ccs6/ccsv6/tools/compiler/c5500_4.4.1/bin/cl55" -v5515 --memory_model=large -g --define=c5535 --display_error_number --diag_warning=225 --ptrdiff_size=16 -z -m"NoiseRemoval Sim.map" --stack_size=0x200 --heap_size=0x400 -i"C:/ti/ccs6/ccsv6/tools/compiler/c5500_4.4.1/lib" -i"G:/Downloads/dsp1-projekat/Projekat_0/NoiseRemoval Sim/c55xx_csl/lib" -i"G:/Downloads/dsp1-projekat/Projekat_0/NoiseRemoval Sim/lib" -i"C:/ti/ccs6/ccsv6/tools/compiler/c5500_4.4.1/include" --reread_libs --display_error_number --warn_sections --xml_link_info="NoiseRemoval Sim_linkInfo.xml" --rom_model --sys_stacksize=0x200 -o "NoiseRemoval Sim.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

NoiseRemoval\ Sim.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: C5500 Hex Utility'
	"C:/ti/ccs6/ccsv6/tools/compiler/c5500_4.4.1/bin/hex55"  -o "NoiseRemoval Sim.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "aic3204.d" "aic3204_init.d" "ezdsp5535_aic3204_dma.d" "iir.d" "main.d" "print_number.d" "window.d" 
	-$(RM) "aic3204.obj" "aic3204_init.obj" "ezdsp5535_aic3204_dma.obj" "iir.obj" "main.obj" "print_number.obj" "window.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

