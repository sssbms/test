import javax.swing.*;

public class AirlineTicketingSystem {
    public static void main(String[] args) {
        SwingUtilities.invokeLater(() -> {
            AirlineTicketingFrame frame = new AirlineTicketingFrame();
            frame.setVisible(true);
        });
    }
}
