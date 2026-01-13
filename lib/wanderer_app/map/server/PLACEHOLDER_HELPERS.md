# Placeholder Systems Helper Module

This module contains helper functions for upgrading placeholder systems to real systems.

## Functions

### find_placeholder_for_connection/2
Finds a placeholder system connected to a parent system via wormhole connection.

### upgrade_placeholder_system/3
Handles the complete upgrade process:
1. Creates real system with placeholder's position
2. Updates all signatures linking to placeholder
3. Transfers connections to real system
4. Deletes the placeholder

### update_signatures_for_placeholder/3
Updates signature `linked_system_id` from placeholder to real system.

### update_connections_for_placeholder/3
Recreates connections with real system ID instead of placeholder ID.
