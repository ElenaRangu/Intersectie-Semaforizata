% Initializarea culorilor situatia 1
% Semafoarele 1
set([TL1g], 'facecolor', [0 1 0])
set([TL1r], 'facecolor', [0.4 0 0])
set([TL1y], 'facecolor', [0.4 0.4 0])
% Semafoarele 2
set([TL2y], 'facecolor', [0.4 0.4 0])
set([TL2g], 'facecolor', [0 0.4 0])
% Semafoarele 3
set([TL3y], 'facecolor', [0.4 0.4 0])
set([TL3g], 'facecolor', [0 0.4 0])
% Semafoarele 4
set([TL4y], 'facecolor', [0.4 0.4 0])
set([TL4g], 'facecolor', [0 0.4 0])
for i = 0.1:0.5:6
pause(0.5)
set(Car1, 'visible', 'off')
Car1 = fill([4.2 4.8 4.8 4.2],[3.8+i 3.8+i 2.8+i 2.8+i], 'k');
set(Car1, 'visible', 'on')
end
pause (0.5)
set(Car1, 'visible', 'off')
% Initializarea culorilor situatia 2
% Semafoarele 1
set([TL1r], 'facecolor', [1 0 0])
set([TL1g], 'facecolor', [0 0.4 0])
% Semafoarele 2
set([TL2r], 'facecolor', [0.4 0 0])
set([TL2g], 'facecolor', [0 1 0])
% Miscarea masinii 2
for i = 0.1:0.5:6
pause(0.5)
set(Car2, 'visible', 'off')
Car2 = fill([6.2-i 7.2-i 7.2-i 6.2-i],[4.2 4.2 4.8 4.8], 'r');
set(Car2, 'visible', 'on')
end
pause
set(Car2, 'visible', 'off')
% Initializarea culorilor situatia 3
% Semafoarele 2
set([TL2r], 'facecolor', [1 0 0])
set([TL2g], 'facecolor', [0 0.4 0])
% Semafoarele 3
set([TL3r], 'facecolor', [0.4 0 0])
set([TL3g], 'facecolor', [0 1 0])
% Miscarea masinii 3
for i = 0.1:0.5:6
pause(0.5)
set(Car3, 'visible', 'off')
Car3 = fill([5.2 5.8 5.8 5.2],[6.2-i 6.2-i 7.2-i 7.2-i], 'b');
set(Car3, 'visible', 'on')
end
pause
set(Car3, 'visible', 'off')
% % Initializarea culorilor situatia 4
% Semafoarele 3
set([TL3r], 'facecolor', [1 0 0])
set([TL3g], 'facecolor', [0 0.4 0])
% Semafoarele 4
set([TL4r], 'facecolor', [0.4 0 0])
set([TL4g], 'facecolor', [0 1 0])
% Miscarea masinii 4
for i = 0.1:0.5:6
pause(0.5)
set(Car4, 'visible', 'off')
Car4 = fill([2.8+i 3.8+i 3.8+i 2.8+i],[5.2 5.2 5.8 5.8], 'm');
set(Car4, 'visible', 'on')
end
pause
set(Car4, 'visible', 'off')