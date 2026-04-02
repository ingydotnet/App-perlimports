M := .cache/makes
$(shell [ -d $M ] || (git clone -q https://github.com/makeplus/makes $M))

include $M/init.mk
include $M/claude.mk
include $M/shell.mk
include $M/clean.mk

# Add files and directories that you need here:
CLAUDE-NONO-R-FILES +=
CLAUDE-NONO-RW-FILES +=
CLAUDE-NONO-R-DIRS +=
CLAUDE-NONO-RW-DIRS +=

claude: claude-nono
