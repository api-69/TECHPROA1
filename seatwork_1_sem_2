public class SeatworkOneThird {
    public static class Buy {
        private String productName;
        private double price;
        private int quantity;

        Buy(String productName, double price, int quantity) {
            this.setProductName(productName);
            this.setPrice(price);
            this.setQuantity(quantity);
        }

        public String getProductName() {
            return productName;
        }

        public double getPrice() {
            return price;
        }

        public int getQuantity() {
            return quantity;
        }

        public void setProductName(String productName) {
            this.productName = productName;
        }

        public void setPrice(double price) {
            this.price = price;
        }

        public void setQuantity(int quantity) {
            this.quantity = quantity;
        }
    }

    public static void main(String[] args) {
        Buy buy = new Buy("Gaming Mouse", 1500.5, 3);

        System.out.println("Product Name: " + buy.getProductName());
        System.out.println("Product Price: " + buy.getPrice());
        System.out.println("Quantity: " + buy.getQuantity());

        double total = buy.getPrice() + buy.getQuantity();

        System.out.println("Total: " + total);
    }
}