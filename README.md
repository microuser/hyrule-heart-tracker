# Micro's Hyrule Heart Tracker

A comprehensive, interactive heart piece tracker for **The Legend of Zelda: Ocarina of Time** with automatic progress saving and detailed collection guides.

## Live Application

**[Access the Live Tracker](https://microuser.github.io/hyrule-heart-tracker/)**

[![Hyrule Heart Tracker](https://img.shields.io/badge/Live%20Application-Available-brightgreen?style=for-the-badge&logo=github)](https://microuser.github.io/hyrule-heart-tracker/)

---

## Overview

This web application provides a complete tracking system for all 36 heart pieces in The Legend of Zelda: Ocarina of Time. The tracker features detailed collection guides, automatic progress persistence, and a retro gaming aesthetic inspired by classic game interfaces.

**Key capabilities:**
- Complete 36 heart piece checklist with detailed instructions
- Video guide integration with timestamp links
- Automatic cookie-based progress saving
- Manual save/load system using hex codes
- Mobile-responsive design
- No external dependencies

---

## Features

### Comprehensive Coverage
- **Complete Documentation**: All 36 heart pieces with step-by-step instructions
- **Multiple Collection Methods**: Alternative approaches documented for each piece
- **Requirement Analysis**: Clear listing of required items, abilities, and story progression
- **Cost Analysis**: Detailed rupee costs for expensive collection methods

### Guide Integration
- **Video References**: Direct links to video guides with precise timestamps
- **Authoritative Sources**: References to established community guides and wikis
- **Difficulty Assessment**: Professional tips for challenging collection scenarios
- **Optimization Notes**: Efficiency recommendations for speedrunners and completionists

### Progress Management
- **Automatic Persistence**: Real-time saving to browser cookies with 1-year retention
- **Manual Backup System**: 64-character hexadecimal save codes for cross-device compatibility
- **Progress Visualization**: Real-time progress tracking with completion statistics
- **Data Recovery**: Robust save/load functionality with error handling

### User Interface
- **Responsive Design**: Optimized for desktop and mobile devices
- **Accessibility Features**: Keyboard navigation and screen reader compatibility
- **Performance Optimized**: Pure vanilla JavaScript with minimal resource usage
- **Visual Feedback**: Clear status indicators and confirmation messages

---

## Technical Implementation

### Architecture
- **Frontend**: Pure HTML5, CSS3, and vanilla JavaScript
- **Storage**: Browser cookies for automatic persistence
- **Encoding**: Binary-to-hexadecimal conversion for compact save codes
- **Compatibility**: Works across all modern browsers without external dependencies

### Data Management
```javascript
// Save system supports up to 256 boolean values (expandable for future features)
function generateCode() {
    // Converts checkbox states to 64-character hex string
    // Compatible with future Gold Skulltula tracking expansion
}
```

### Performance Characteristics
- **Load Time**: < 1 second on standard connections
- **Memory Usage**: Minimal footprint with efficient DOM manipulation
- **Storage**: 64 bytes per save state with optional cookie persistence
- **Browser Support**: Compatible with all browsers supporting ES6+

---

## Heart Piece Organization

The application organizes heart pieces by **game progression requirements** rather than geographical location, enabling optimal collection routing:

### Early Game (Child Link - Basic Equipment)
- Graveyard Royal Family's Tomb challenge
- Lost Woods musical interactions
- Lon Lon Ranch exploration
- Hyrule Market questlines
- Goron City timing challenges

### Mid Game (Song-Dependent Collections)
- Zora's Domain torch sequences
- Zora's River frog interactions
- Musical challenge completions

### Advanced Child Link (Specialized Equipment)
- Bombchu Bowling Alley competitions
- Treasure Chest Game completion
- Cucco transportation challenges
- Advanced platforming techniques

### Adult Link Progression
- Hookshot and Longshot dependent locations
- Magic Bean platform utilization
- Advanced dungeon preparation pieces

### Late Game Collections
- Mountain and ice area challenges
- Desert region completions
- Final Magic Bean platform rewards

---

## Usage Instructions

### Getting Started
1. Navigate to the live application at https://microuser.github.io/hyrule-heart-tracker/
2. Begin checking off heart pieces as you collect them in-game
3. Progress automatically saves to browser cookies

### Save System Options

**Automatic (Recommended)**
- Progress saves automatically on each checkbox interaction
- Data persists for one year in browser storage
- No manual intervention required

**Manual Backup**
- Generate 64-character hex codes for external storage
- Load codes to restore progress across devices
- Useful for sharing completion status or creating backups

### Advanced Features
- Use the hex code system for progress sharing between users
- Clear function available for starting new playthroughs
- Progress statistics provide completion tracking

---

## Development Information

### Project Structure
```
hyrule-heart-tracker/
├── index.html          # Main application file
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── docs/               # Additional documentation
```

### Contributing
Contributions are welcome for the following enhancements:

**Feature Expansion**
- Gold Skulltula tracking integration (100 tokens)
- Additional Zelda game support
- Theme customization options
- Internationalization support

**Technical Improvements**
- Accessibility enhancements
- Performance optimizations
- Additional save format support
- Progressive Web App features

### Development Setup
```bash
git clone https://github.com/microuser/hyrule-heart-tracker.git
cd hyrule-heart-tracker
# Open index.html in browser - no build process required
```

---

## Reference Information

### Cost Analysis
- **Most Expensive Collections**: Desert Colossus (100 rupees), Death Mountain Crater (90 rupees)
- **Time-Investment Pieces**: Dampe's random digging game, Frog orchestra sequence
- **Skill-Based Challenges**: Gerudo Fortress navigation, horseback archery

### Time-Sensitive Collections
- **Night-Only Access**: Dampe's tours, Treasure Chest Game, Market dog quest
- **Story-Dependent**: Several pieces require specific story progression milestones
- **Equipment-Gated**: Many pieces impossible without specific items or abilities

### Optimization Notes
- **Total Magic Bean Investment**: 640 rupees across all 10 bean locations
- **Song Learning Order**: Critical for accessing time-dependent pieces
- **Equipment Prioritization**: Hookshot, Longshot, and scale upgrades enable multiple pieces

---

## Links and Resources

- **Live Application**: https://microuser.github.io/hyrule-heart-tracker/
- **Source Code**: https://github.com/microuser/hyrule-heart-tracker/blob/main/index.html
- **Primary Reference**: Zelda Dungeon Wiki Heart Pieces Guide
- **Video Integration**: Individual timestamp links provided per heart piece

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgments

Built for the Zelda speedrunning and completion community. Special recognition to the comprehensive guides from Zelda Dungeon, GameFAQs contributors, and the broader Ocarina of Time community for their detailed documentation of heart piece locations and collection strategies.
