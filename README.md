#include <asm/irq_regs.h>
#include <asm/ptrace.h>
struct profile_hit {
	u32 pc, hits;
};
#define PROFILE_GRPSHIFT
